# CALCULATOR-APP
easy and shortcut method for calculating 
    .calculator {
        background: #333;
        border-radius: 20px;
        padding: 20px;
        box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.2);
        animation: fadeIn 1.2s ease-in-out;
    }

    @keyframes fadeIn {
        from {
            opacity: 0;
            transform: scale(0.8);
        }
        to {
            opacity: 1;
            transform: scale(1);
        }
    }

    .screen {
        text-align: right;
        margin-bottom: 20px;
    }

    .screen input {
        width: 100%;
        height: 60px;
        background: #222;
        border: none;
        border-radius: 10px;
        color: #fff;
        font-size: 2rem;
        padding: 10px;
        box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
        animation: slideIn 0.6s ease-out;
    }

    @keyframes slideIn {
        from {
            transform: translateY(-50px);
            opacity: 0;
        }
        to {
            transform: translateY(0);
            opacity: 1;
        }
    }

    .buttons {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 10px;
    }

    button {
        background-color: #444;
        color: white;
        font-size: 1.5rem;
        padding: 20px;
        border: none;
        border-radius: 10px;
        cursor: pointer;
        transition: transform 0.2s, background-color 0.3s;
    }

    button:hover {
        background-color: #555;
        transform: scale(1.1);
    }

    button:active {
        transform: scale(0.95);
    }

    button.equal {
        background-color: #ff9800;
        color: white;
        grid-column: span 2;
    }

    button.equal:hover {
        background-color: #e68a00;
    }
</style>
