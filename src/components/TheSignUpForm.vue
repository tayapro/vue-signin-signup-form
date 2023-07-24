<template>
    <div>
        <div>
            <div class="labels"><label>Username or email </label></div>
            <div class="input-container">
                <input type="text" placeholder="login" />
            </div>
            <div class="labels"><label>E-mail</label></div>
            <div class="input-container">
                <input type="text" placeholder="e-mail" />
            </div>
            <div class="labels"><label>Password</label></div>
            <div class="input-container">
                <input type="text" placeholder="password" />
            </div>
            <div class="btn-send">
                <button>Submit</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.input-container {
    display: flex;
}
.btn-send {
    margin-top: 0.5rem;
    text-align: center;
}

.labels {
    margin-bottom: 0.2rem;
}

input {
    border: 2px solid rgba(67, 67, 68, 0.599);
    border-radius: 5px;
    flex-grow: 1;
    padding: 0.5rem;
    margin-bottom: 0.5rem;
}

input:focus {
    outline: none;
    border: 1px solid rgb(220, 31, 198);
}

button {
    border: none;
    background-color: rgb(105, 105, 106);
    border-radius: 5px;
    color: aliceblue;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: rgb(220, 31, 198);
    border-color: rgb(220, 31, 198);
}
</style>
