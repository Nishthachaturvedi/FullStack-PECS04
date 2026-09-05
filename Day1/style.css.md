* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background: #f4f6f8;
    color: #222;
}

header {
    background: #4f46e5;
    color: white;
    text-align: center;
    padding: 25px 15px;
}

header h1 {
    font-size: 32px;
}

main {
    min-height: calc(100vh - 82px);
    display: flex;
    justify-content: center;
    align-items: flex-start;
    padding: 50px 20px;
}

.task-manager {
    width: 100%;
    max-width: 600px;
    background: white;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
}

.task-manager h2 {
    margin-bottom: 18px;
}

form {
    display: flex;
    gap: 10px;
}

input {
    flex: 1;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 16px;
}

button {
    padding: 12px 22px;
    border: none;
    border-radius: 6px;
    background: #4f46e5;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

.task-list {
    margin-top: 35px;
}

.task-list ul {
    min-height: 80px;
    border: 2px dashed #ddd;
    border-radius: 8px;
    padding: 20px;
    list-style-position: inside;
}

@media (max-width: 600px) {
    main {
        padding: 25px 15px;
    }

    .task-manager {
        padding: 20px;
    }

    form {
        flex-direction: column;
    }

    button {
        width: 100%;
    }

    header h1 {
        font-size: 26px;
    }
}
