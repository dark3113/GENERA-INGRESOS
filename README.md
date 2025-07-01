<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Gana dinero!</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

        :root {
            --primary-color: #1e88e5; /* Blue */
            --secondary-color: #1565c0; /* Darker Blue */
            --background-color: #f4f6f8; /* Light Gray */
            --text-color: #212121;
            --button-hover-color: #0d47a1; /* Darker Blue */
            --white: #fff;
            --shadow-color: rgba(0, 0, 0, 0.1);
            --border-radius: 8px;
            --transition-speed: 0.3s;
        }

        body {
            font-family: 'Montserrat', Arial, sans-serif;
            text-align: center;
            background-color: var(--background-color);
            margin: 0;
            color: var(--text-color);
            line-height: 1.6;
        }

        #header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: var(--secondary-color);
            padding: 15px 30px;
            box-shadow: 0 4px 8px var(--shadow-color);
            color: var(--white);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        #menu {
            position: relative;
            display: inline-block;
        }

        #menuButton {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            border-radius: var(--border-radius);
            font-weight: 700;
            font-size: 16px;
            transition: background-color var(--transition-speed);
            box-shadow: 0 2px 5px var(--shadow-color);
        }

        #menuButton:hover {
            background-color: var(--button-hover-color);
        }

        #menuContent {
            display: none;
            position: absolute;
            background-color: var(--white);
            min-width: 200px;
            box-shadow: 0 8px 16px var(--shadow-color);
            border-radius: var(--border-radius);
            padding: 15px;
            z-index: 1100;
            transition: opacity var(--transition-speed);
        }

        #menuContent.show {
            display: block;
            opacity: 1;
        }

        #menuContent input, #menuContent select {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: var(--border-radius);
            font-size: 14px;
            transition: border-color var(--transition-speed);
        }

        #menuContent input:focus, #menuContent select:focus {
            border-color: var(--primary-color);
            outline: none;
        }

        #saveAccount {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 12px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: var(--border-radius);
            font-weight: 700;
            font-size: 16px;
            transition: background-color var(--transition-speed);
            box-shadow: 0 2px 5px var(--shadow-color);
            margin-top: 10px;
        }

        #saveAccount:hover {
            background-color: var(--button-hover-color);
        }

        #counter, #paymentValue, #message {
            font-size: 26px;
            background-color: var(--white);
            padding: 12px 20px;
            border-radius: var(--border-radius);
            margin: 15px 0;
            box-shadow: 0 2px 5px var(--shadow-color);
            color: var(--text-color);
            display: inline-block;
            min-width: 220px;
        }

        #confirmedAccount {
            font-weight: 600;
            color: var(--primary-color);
            margin-left: 20px;
            font-size: 18px;
        }

        #clickButton {
            background: linear-gradient(45deg, #1e88e5, #1565c0);
            color: var(--white);
            font-size: 24px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            display: block;
            margin: 20px auto;
            padding: 20px 40px;
            border-radius: var(--border-radius);
            box-shadow: 0 4px 10px var(--shadow-color);
            user-select: none;
        }

        #clickButton:hover {
            box-shadow: 0 6px 14px rgba(30, 136, 229, 0.7);
            transform: translateY(-2px);
        }

        #clickButton:active {
            transform: scale(0.95);
            box-shadow: 0 2px 6px var(--shadow-color);
        }

        #progressBar {
            width: 80%;
            max-width: 600px;
            background-color: #ddd;
            border-radius: var(--border-radius);
            margin: 25px auto;
            height: 14px;
            box-shadow: inset 0 1px 3px #bbb;
        }

        #progressBarFill {
            width: 0%;
            height: 100%;
            background: linear-gradient(90deg, #1e88e5, #1565c0);
            border-radius: var(--border-radius);
            transition: width 0.4s ease;
        }

        #registrationSection, #withdrawalSection, #referralSection, #loginSection {
            margin: 30px auto;
            padding: 25px 30px;
            background-color: var(--white);
            border-radius: var(--border-radius);
            box-shadow: 0 4px 8px var(--shadow-color);
            max-width: 400px;
            text-align: left;
        }

        #registrationSection h2, #withdrawalSection h2, #referralSection h2, #loginSection h2 {
            margin-top: 0;
            font-weight: 700;
            color: var(--primary-color);
            font-size: 22px;
        }

        #registrationSection input, #loginSection input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: var(--border-radius);
            font-size: 16px;
            transition: border-color var(--transition-speed);
        }

        #registrationSection input:focus, #loginSection input:focus {
            border-color: var(--primary-color);
            outline: none;
        }

        #registerButton, #withdrawButton {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 14px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: var(--border-radius);
            font-weight: 700;
            font-size: 18px;
            transition: background-color var(--transition-speed);
            box-shadow: 0 4px 8px var(--shadow-color);
            margin-top: 15px;
        }

        #registerButton:hover, #withdrawButton:hover {
            background-color: var(--button-hover-color);
        }

        #referralCode {
            font-size: 18px;
            color: var(--text-color);
            margin-top: 10px;
            font-weight: 600;
        }

        .error {
            color: #d32f2f;
            font-size: 14px;
            margin-top: 5px;
        }

        #clickInstructions, #clickMessage, #message {
            font-size: 18px;
            color: var(--text-color);
            margin: 15px auto;
            max-width: 600px;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            #header {
                flex-direction: column;
                align-items: flex-start;
                padding: 15px;
            }

            #counter, #paymentValue {
                font-size: 20px;
                min-width: auto;
                margin: 8px 0;
            }

            #clickButton {
                width: 90%;
                font-size: 20px;
                padding: 15px 0;
            }

            #registrationSection, #withdrawalSection, #referralSection, #loginSection {
                width: 90%;
                padding: 20px;
                margin: 20px auto;
            }
        }

        footer {
            background-color: var(--secondary-color);
            color: var(--white);
            text-align: center;
            padding: 15px 0;
            font-size: 14px;
            box-shadow: 0 -2px 5px var(--shadow-color);
            margin-top: 40px;
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            let clickCount = 0;
            const elements = {
                button: document.getElementById('clickButton'),
                counter: document.getElementById('counter'),
                message: document.getElementById('message'),
                paymentValue: document.getElementById('paymentValue'),
                progressBarFill: document.getElementById('progressBarFill'),
                menuButton: document.getElementById('menuButton'),
                menuContent: document.getElementById('menuContent'),
                accountTypeSelect: document.getElementById('accountType'),
                confirmedAccount: document.getElementById('confirmedAccount'),
                withdrawalAmount: document.getElementById('withdrawalAmount'),
                referralCode: document.getElementById('referralCode'),
                registrationSection: document.getElementById('registrationSection'),
                registerButton: document.getElementById('registerButton'),
                regUsername: document.getElementById('regUsername'),
                regPassword: document.getElementById('regPassword'),
                regReferralCode: document.getElementById('regReferralCode'),
                errorMessage: document.getElementById('errorMessage')
            };
            const valuePerClick = 0.001;

            elements.button.onclick = function() {
                clickCount++;
                elements.counter.innerHTML = 'Coins: ' + clickCount + ' 💰';
                elements.paymentValue.innerHTML = 'Valor por clic: $' + (clickCount * valuePerClick).toFixed(3);
                elements.progressBarFill.style.width = (clickCount % 10) * 10 + '%';

                if (clickCount % 10 === 0) {
                    window.open('https://momrollback.com/hb9azvwh?key=fe2a96dfe0db335c8c14e11ddf65413e', '_blank');
                }
                if (clickCount % 2 === 0) {
                    elements.message.innerHTML = '¡Sigue haciendo clic para ganar más!';
                }
            };

            elements.menuButton.onclick = function() {
                elements.menuContent.style.display = elements.menuContent.style.display === 'block' ? 'none' : 'block';
            };

            elements.accountTypeSelect.onchange = function() {
                const selectedType = elements.accountTypeSelect.value;
                const accountTypeDetails = document.getElementById('accountTypeDetails');
                accountTypeDetails.innerHTML = selectedType === 'Bancolombia' ? `
                    <select id="accountSubType">
                        <option value="Ahorro">Ahorro</option>
                        <option value="Corriente">Corriente</option>
                    </select>
                    <input type="text" id="accountNumber" placeholder="Número de cuenta (11 dígitos)" maxlength="11">
                ` : selectedType === 'Nequi' ? `
                    <input type="text" id="accountNumber" placeholder="Número de cuenta (11 dígitos)" maxlength="11">
                ` : '';
            };

            document.getElementById('saveAccount').onclick = function() {
                const accountNumber = document.getElementById('accountNumber').value;
                if (accountNumber.length === 11) {
                    elements.confirmedAccount.innerHTML = 'Cuenta Confirmada: ' + accountNumber;
                    elements.menuContent.style.display = 'none';
                } else {
                    alert('El número de cuenta debe tener 11 dígitos.');
                }
            };

            document.getElementById('withdrawButton').onclick = function() {
                const amount = withdrawalAmount.value;
                const requiredPoints = {
                    '20': 20000,
                    '50': 50000,
                    '100': 100000,
                    '200': 200000,
                    '500': 500000,
                    '1000': 1000000
                };
                if (clickCount >= requiredPoints[amount]) {
                    alert('Solicitud de retiro por $' + amount + ' enviada.');
                } else {
                    alert('No tienes suficientes puntos para este retiro. Necesitas ' + requiredPoints[amount] + ' puntos.');
                }
            };

            const generateReferralCode = () => 'REF' + Math.floor(Math.random() * 10000);
            const displayReferralCode = () => {
                elements.referralCode.innerHTML = 'Tu código de referido es: ' + generateReferralCode();
            };

            elements.registerButton.onclick = function() {
                const username = elements.regUsername.value.trim();
                const password = elements.regPassword.value.trim();
                const referralCode = elements.regReferralCode.value.trim();
                let valid = true;

                // Clear previous error messages
                elements.errorMessage.innerHTML = '';

                // Validate username
                if (username.length < 3) {
                    elements.errorMessage.innerHTML += '<p class="error">El nombre de usuario debe tener al menos 3 caracteres.</p>';
                    valid = false;
                }

                // Validate password
                if (password.length < 6) {
                    elements.errorMessage.innerHTML += '<p class="error">La contraseña debe tener al menos 6 caracteres.</p>';
                    valid = false;
                }

                if (valid) {
                    // Clear registration fields
                    elements.regUsername.value = '';
                    elements.regPassword.value = '';
                    elements.regReferralCode.value = '';
                    registrationSection.style.display = 'none';
                    elements.button.style.display = 'block';
                    document.getElementById('clickInstructions').style.display = 'block';
                    document.getElementById('clickMessage').style.display = 'block';
                    document.getElementById('withdrawalSection').style.display = 'block';
                    document.getElementById('referralSection').style.display = 'block';
                    elements.counter.style.display = 'block';
                    elements.paymentValue.style.display = 'block';
                    elements.message.style.display = 'block';
                    displayReferralCode();
                }
            };
        });
    </script>
</head>
<body>
    <div id="header">
        <div id="menu">
            <button id="menuButton">Menu</button>
            <div id="menuContent">
                <select id="accountType">
                    <option value="">Selecciona el tipo de cuenta</option>
                    <option value="Nequi">Nequi</option>
                    <option value="Bancolombia">Bancolombia</option>
                </select>
                <div id="accountTypeDetails"></div>
                <button id="saveAccount">Guardar</button>
            </div>
        </div>
        <div id="counter">Coins: 0 💰</div>
        <div id="paymentValue">Valor por clic: $0.00</div>
        <div id="confirmedAccount"></div>
    </div>
    <h1>¡Gana dinero!</h1>
    <div id="registrationSection">
        <h2>Registro</h2>
        <div id="errorMessage" class="error"></div>
        <input type="text" id="regUsername" placeholder="Usuario" required>
        <input type="password" id="regPassword" placeholder="Contraseña" required>
        <input type="text" id="regReferralCode" placeholder="Código de Referido" required>
        <button id="registerButton">Registrarse</button>
    </div>
    <div id="loginSection" style="display: none;">
        <h2>Iniciar Sesión</h2>
        <input type="text" id="username" placeholder="Usuario" required>
        <input type="password" id="password" placeholder="Contraseña" required>
        <input type="text" id="referralCodeInput" placeholder="Código de Referido" required>
        <button id="loginButton">Iniciar Sesión</button>
    </div>
    <button id="clickButton" style="display: none;">💰 ¡Gana dinero! 💰</button>
    <div id="progressBar" style="display: none;">
        <div id="progressBarFill"></div>
    </div>
    <p id="clickInstructions" style="display: none;">Haz clic en el botón para ganar dinero con los anuncios que mostramos. Después de 10 clics se abrirá un nuevo anuncio, con estos podemos darte las recompensas que ofrecemos</p>
    <p id="clickMessage" style="display: none;">¡Haz clic y gana!</p>
    <div id="message" style="display: none;"></div>
    <div id="withdrawalSection" style="display: none;">
        <h2>Retiro</h2>
        <select id="withdrawalAmount">
            <option value="20">Retiro de $20 (20,000 puntos)</option>
            <option value="50">Retiro de $50 (50,000 puntos)</option>
            <option value="100">Retiro de $100 (100,000 puntos)</option>
            <option value="200">Retiro de $200 (200,000 puntos)</option>
            <option value="500">Retiro de $500 (500,000 puntos)</option>
            <option value="1000">Retiro de $1000 (1,000,000 puntos)</option>
        </select>
        <button id="withdrawButton">Solicitar Retiro</button>
    </div>
    <div id="referralSection" style="display: none;">
        <h2>Referidos</h2>
        <p id="referralCode"></p>
        <p>Comparte tu código con amigos para que se registren y ganes recompensas. Por cada referido que complete sus primeros 1000 puntos, recibirás 2000 puntos.</p>
    </div>
</body>
</html>
