<template>
    <div class = "question">
        <div class = "header">
            {{header}}
        </div>
        <div class = "contentBox">
            <p>{{content}}</p>
            <div class = "answerBox">
                <div>
                    {{answerPrompt}} <input type="text" value="">
                </div>
                <div class = "submitButton">
                    <input type="button" value="Submit Answer">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Question",
    
    props: {
        header: String,
        content: String,
        answerPrompt: String
    }
}
</script>

<style scoped>
    .question {
        margin: 10px;
    }
    .header {
        padding: 4px;
        background-color: #dddddd;
        border-color: #aaaaaa;
        border-style: solid;
        border-width: 2px;
        font-size: 16pt;
        
    }
    .contentBox {
        padding: 4px 10px;
        margin-left: 10px;
        border-color: #aaaaaa;
        border-style: solid;
        border-width: 1px;
    }
    .submitButton {
        padding: 5px 0;
    }
</style>