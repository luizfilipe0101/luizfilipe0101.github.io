<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luiz Filipe | Psicólogo Clínico</title>
    <!-- Google Fonts: Playfair Display & Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Playfair+Display:ital,wght@0,500;0,600;1,400&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-color: #1a1a1a;
            --card-bg: #242424;
            --gold-primary: #d4af37;
            --gold-gradient: linear-gradient(135deg, #f3e5ad 0%, #c5a028 50%, #997a15 100%);
            --text-primary: #e0e0e0;
            --text-secondary: #a0a0a0;
            --border-color: #333333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-primary);
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 680px;
            width: 100%;
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 40px 30px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.5);
            text-align: center;
            position: relative;
        }

        /* Logo / Header */
        .logo-container {
            margin-bottom: 25px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo-icon {
            width: 360px;
            height: auto;
            filter: drop-shadow(0px 4px 8px rgba(0,0,0,0.6));
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            font-weight: 600;
            background: var(--gold-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 5px;
        }

        .subtitle {
            font-size: 1rem;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 500;
            margin-bottom: 20px;
        }

        .crp-badge {
            display: inline-block;
            font-size: 0.85rem;
            color: var(--gold-primary);
            border: 1px solid rgba(212, 175, 55, 0.3);
            padding: 4px 12px;
            border-radius: 20px;
            margin-bottom: 30px;
        }

        /* Divider */
        .divider {
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--border-color), transparent);
            margin: 30px 0;
        }

        /* About Section */
        .about-text {
            font-size: 0.95rem;
            color: var(--text-primary);
            font-weight: 300;
            margin-bottom: 30px;
            text-align: justify;
            text-justify: inter-word;
        }

        /* Contract & Guidelines Section */
        .info-box {
            background: rgba(0, 0, 0, 0.2);
            border-left: 3px solid var(--gold-primary);
            padding: 15px 20px;
            text-align: left;
            border-radius: 0 8px 8px 0;
            margin-bottom: 30px;
            font-size: 0.88rem;
            color: var(--text-secondary);
        }

        .info-box h3 {
            color: var(--gold-primary);
            font-size: 0.95rem;
            margin-bottom: 8px;
            font-weight: 500;
        }

        .info-box ul {
            list-style: none;
            padding-left: 0;
        }

        .info-box li {
            margin-bottom: 6px;
            position: relative;
            padding-left: 15px;
        }

        .info-box li::before {
            content: "•";
            color: var(--gold-primary);
            position: absolute;
            left: 0;
        }

        /* CTA Button */
        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 16px;
            background: var(--gold-gradient);
            color: #111;
            font-size: 1rem;
            font-weight: 600;
            text-decoration: none;
            border-radius: 8px;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.2);
        }

        .btn-whatsapp:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(212, 175, 55, 0.35);
        }

        /* Footer */
        footer {
            margin-top: 30px;
            font-size: 0.75rem;
            color: var(--text-secondary);
        }

        @media (max-width: 480px) {
            .container {
                padding: 30px 20px;
            }
            h1 {
                font-size: 1.6rem;
            }
            .logo-icon {
                width: 90px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo SVG com aplicação do Gradiente Dourado -->
        <div class="logo-container">
            <svg class="logo-icon" version="1.0" xmlns="http://www.w3.org/2000/svg"
                 width="1408.000000pt" height="768.000000pt" viewBox="0 0 1408.000000 768.000000"
                 preserveAspectRatio="xMidYMid meet">
                <defs>
                    <linearGradient id="gold-grad" x1="0%" y1="0%" x2="100%" y2="100%">
                        <stop offset="0%" stop-color="#f3e5ad" />
                        <stop offset="50%" stop-color="#c5a028" />
                        <stop offset="100%" stop-color="#997a15" />
                    </linearGradient>
                </defs>
                <g transform="translate(0.000000,768.000000) scale(0.100000,-0.100000)"
                   fill="url(#gold-grad)" stroke="none">
                    <path d="M4903 6560 c-92 -185 -129 -352 -120 -545 13 -290 136 -547 366 -768
                    104 -99 88 -97 -63 11 -209 150 -376 370 -453 597 l-27 80 -9 -70 c-4 -38 -5
                    -117 -2 -175 20 -364 178 -631 473 -800 62 -36 172 -84 172 -76 0 2 -17 15
                    -38 29 -163 107 -327 304 -404 482 l-26 60 102 -100 c119 -118 200 -173 481
                    -330 116 -65 245 -142 288 -172 79 -56 185 -153 226 -207 36 -49 33 -24 -9 57
                    -74 146 -140 217 -375 405 -283 226 -422 396 -514 628 -59 149 -80 282 -72
                    459 l2 60 33 -90 c125 -341 364 -620 731 -850 49 -31 168 -95 265 -142 96 -47
                    205 -106 242 -130 229 -151 324 -318 364 -643 19 -156 38 -238 75 -316 30 -63
                    98 -148 149 -184 27 -19 26 -17 -17 68 -71 142 -86 216 -87 427 0 194 12 285
                    59 450 33 113 108 271 168 351 l45 61 -70 5 c-71 6 -122 28 -62 28 40 0 118
                    28 223 78 132 65 211 65 265 1 21 -25 32 -29 74 -29 48 0 159 -27 149 -36 -3
                    -3 -33 -9 -68 -14 -213 -30 -428 -269 -512 -568 -20 -73 -21 -101 -25 -589 -2
                    -349 -7 -513 -14 -513 -27 0 -137 34 -182 57 -27 14 -76 50 -107 80 -105 100
                    -151 224 -169 461 -23 302 -39 383 -95 497 -41 86 -103 151 -184 193 -66 36
                    -194 72 -253 72 -35 0 -38 -2 -38 -28 0 -25 6 -30 41 -41 58 -18 121 -80 154
                    -153 34 -76 51 -182 64 -418 6 -102 18 -215 26 -251 29 -135 93 -267 169 -348
                    97 -104 282 -197 449 -225 20 -4 37 -9 37 -12 0 -17 -84 -129 -144 -191 -324
                    -342 -825 -442 -1259 -252 -51 22 -98 43 -106 46 -33 14 29 -67 124 -163 158
                    -160 317 -239 507 -251 250 -17 513 100 660 294 68 89 67 93 -4 28 -162 -148
                    -410 -238 -608 -221 -73 7 -187 33 -194 45 -2 3 49 7 113 7 413 5 779 245 905
                    594 12 32 24 58 29 59 4 0 23 1 42 1 l35 0 0 -77 0 -78 30 63 c16 35 64 113
                    105 172 94 136 132 215 145 305 5 39 10 174 10 302 l0 231 -40 75 c-49 91 -74
                    197 -64 276 6 55 39 157 52 165 4 2 7 -33 8 -78 2 -121 16 -153 172 -383 68
                    -99 86 -159 86 -293 1 -87 -4 -128 -18 -170 -26 -78 -81 -181 -122 -228 -19
                    -22 -34 -43 -34 -47 0 -3 21 9 48 27 105 72 191 190 227 308 9 30 25 141 35
                    245 24 235 40 305 95 420 91 188 180 264 509 432 248 128 431 245 562 360 207
                    183 366 412 440 633 l32 95 7 -49 c17 -108 -15 -333 -64 -453 -108 -269 -233
                    -419 -584 -696 -161 -126 -251 -228 -309 -344 -23 -46 -39 -85 -37 -88 3 -2
                    23 18 44 46 87 110 205 194 510 364 280 156 331 191 458 316 110 108 117 109
                    64 4 -77 -153 -206 -307 -345 -410 -44 -33 -79 -61 -78 -63 7 -6 159 69 224
                    111 261 169 403 429 419 767 3 69 3 152 -1 184 l-8 59 -25 -74 c-88 -263 -299
                    -516 -558 -669 -32 -19 -18 -1 67 87 235 243 338 481 339 783 0 187 -37 337
                    -128 512 l-48 93 -6 -135 c-18 -357 -147 -639 -418 -911 -157 -156 -300 -254
                    -597 -407 -115 -59 -241 -129 -279 -154 -196 -130 -327 -329 -366 -555 -11
                    -62 -13 -66 -26 -48 -166 231 -189 281 -181 394 7 88 39 160 98 215 76 71 122
                    90 213 91 70 0 77 2 77 20 0 31 -56 121 -89 144 -35 26 -104 51 -137 51 -13 0
                    -44 16 -69 35 -104 79 -201 75 -397 -16 -172 -80 -258 -96 -354 -63 -25 8 -48
                    14 -50 11 -2 -2 8 -26 22 -54 28 -58 100 -129 145 -145 16 -5 29 -14 29 -18 0
                    -4 -20 -46 -45 -92 -53 -99 -70 -144 -100 -258 l-22 -84 -25 54 c-77 167 -235
                    305 -499 436 -166 82 -353 188 -439 249 -223 157 -391 347 -502 570 -93 184
                    -136 347 -147 550 l-6 120 -52 -105z"/>
                    <path d="M9443 5127 c-50 -69 -157 -173 -244 -237 -107 -78 -244 -144 -444
                    -215 -281 -100 -416 -173 -514 -281 -48 -52 -111 -147 -111 -167 0 -5 26 15
                    58 43 116 105 254 171 580 279 207 68 298 107 382 164 139 94 241 223 305 388
                    14 34 23 64 22 66 -2 2 -17 -16 -34 -40z"/>
                    <path d="M4610 5153 c0 -7 18 -51 40 -99 87 -188 207 -312 397 -408 28 -14
                    154 -60 280 -102 326 -108 462 -176 581 -287 28 -28 52 -46 52 -41 0 27 -73
                    129 -139 195 -112 112 -222 170 -506 269 -164 57 -347 147 -441 218 -77 59
                    -198 177 -242 237 -12 17 -22 24 -22 18z"/>
                    <path d="M8080 4894 c-149 -32 -278 -129 -338 -254 -41 -87 -68 -230 -82 -430
                    -19 -287 -59 -410 -167 -519 -59 -58 -112 -88 -239 -135 -83 -31 -136 -74
                    -205 -164 -108 -143 -149 -273 -149 -476 -1 -373 -46 -457 -262 -491 -34 -5
                    -38 -9 -38 -35 l0 -30 445 0 445 0 0 29 c0 28 -2 29 -66 41 -137 23 -195 78
                    -223 208 -7 34 -11 187 -11 420 l0 367 102 18 c196 33 329 93 444 200 159 148
                    216 314 234 687 13 279 47 395 136 468 19 16 52 34 73 41 37 11 53 32 44 59
                    -6 16 -60 14 -143 -4z"/>
                    <path d="M5021 4478 c99 -197 270 -330 486 -378 289 -65 402 -111 499 -206 30
                    -29 54 -48 54 -43 0 24 -56 117 -98 162 -93 99 -168 136 -404 198 -223 58
                    -334 115 -486 247 l-73 64 22 -44z"/>
                    <path d="M9014 4461 c-82 -77 -201 -154 -295 -191 -42 -16 -139 -46 -215 -66
                    -215 -56 -301 -99 -386 -193 -39 -43 -98 -143 -98 -166 0 -3 25 20 56 50 87
                    85 200 136 409 184 94 22 193 48 220 58 134 51 266 173 340 314 20 38 35 69
                    33 69 -2 -1 -31 -27 -64 -59z"/>
                    <path d="M6766 3089 c-108 -268 -368 -487 -645 -544 -41 -9 -77 -18 -79 -19
                    -2 -2 36 -9 83 -16 352 -50 648 200 672 568 3 45 4 82 2 82 -2 0 -17 -32 -33
                    -71z"/>
                </g>
            </svg>
        </div>

        <!-- Nome e Título -->
        <h1>Luiz Filipe da Cruz Proença</h1>
        <div class="subtitle">Psicólogo Clínico</div>
        <div class="crp-badge">CRP-04 / 86683</div>

        <!-- Sobre Mim -->
        <div class="about-text">
            Ofereço atendimento psicológico focado em proporcionar um espaço ético, seguro e acolhedor para a sua jornada de autoconhecimento e saúde mental. As sessões ocorrem na modalidade <strong>online</strong>, garantindo flexibilidade e sigilo profissional.
        </div>

        <!-- Orientações do Atendimento / Contrato -->
        <div class="info-box">
            <h3>Informações sobre o Atendimento Online</h3>
            <ul>
                <li><strong>Confirmação de Agendamento:</strong> Realizada mediante pagamento prévio via PIX (até 24h antes da sessão).</li>
                <li><strong>Duração:</strong> As sessões têm duração média de 50 minutos.</li>
                <li><strong>Sigilo & Segurança:</strong> Plataforma criptografada em conformidade com as diretrizes do CFP e E-Psi.</li>
            </ul>
        </div>

        <!-- Botão CTA -->
        <a href="https://wa.me/5532998004360?text=Olá,%20gostaria%20de%20informações%20sobre%20agendamento%20de%20consulta." target="_blank" class="btn-whatsapp">
            Agendar Consulta via WhatsApp
        </a>

        <div class="divider"></div>

        <!-- Rodapé -->
        <footer>
            <p>© 2026 Luiz Filipe da Cruz Proença. Todos os direitos reservados.</p>
            <p>Plataforma autorizada pelo Conselho Federal de Psicologia.</p>
        </footer>
    </div>

</body>
</html>
