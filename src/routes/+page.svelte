
<style >

.card {
    width: 90vw;
    height: 90vh;
    padding: 2rem;
    background: rgba(255, 255, 255, .7);
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
    border-radius: 1rem;
    overflow-y: auto;
}

.card-title {
    margin-top: 0;
    margin-bottom: .5rem;
    font-size: 1.9rem;
}

p {
    font-size: 1rem;
}


.message{
    position: absolute;
    width: 70vw;
}
.msg {
    background-color: cadetblue;
    /* width: 24%; */
    padding: 10px;
    margin: 15px 10px;
    border-radius: 8px;
}
.left {
    clear: both;
    float: left;
    background-color: rgb(198, 212, 212);
}
.right {
    float: right;
    clear: both;
}

.inp {
    height: 155px;
    width: 70vw;
    position: absolute;
    margin-top: 60vh;
    border-bottom-right-radius: 20px;
}
.inp textarea {
    margin-top: -190px;
    background-color: white;
    padding: 12px;
    font-size: 20px;
    height: 150px;
    width: 80vw;
    border-radius: 20px;
    outline: none;
    border: none;
    position: absolute;
}

</style>

<div class="card">
    <div class="container">
        <h3 class="card-title">IntegratedML Depression Prediction</h3>
        <p>Having a low mood or feeling on edge are common experiences for us all. When these moods persist, it may be that you are experiencing depression.</p>
        <br/>
        <h3>Disclaimer!</h3>
        <p>This is NOT a diagnostic tool. Mental health disorders can only be diagnosed by a licensed mental health provider or doctor.</p>
        <br/>
        <h4>Over the past two weeks, how would you describe your overall emotional state? </h4>
    </div>

    <div class="prompt">
        <div class="message">
            <div class="msg left">
                Would you say you've been feeling generally "okay" or "good," or have you been experiencing more challenging emotions such as embarrassment, unease, or frustration? Perhaps you've been feeling curious, energetic, or protective, or maybe you've been struggling with feelings of resistance, anger, or disappointment.
            </div>
            <div class="msg right">
            </div>
        </div>

        <div class="inp">
            <div class="emoji"><img src="emoji.png" alt=""></div>
            <textarea id="desc" rows="1" placeholder="Describe your feelings here..."></textarea>
        </div>
    </div>
</div>