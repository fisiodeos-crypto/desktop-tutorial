
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fisioterapia | Saúde e Movimento</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #f5f9fc;
    color: #263746;
}

header {
    background: #075985;
    color: white;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
}

.logo {
    font-size: 25px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}

nav a:hover {
    color: #a7f3d0;
}

.hero {
    min-height: 430px;
    padding: 80px 8%;
    display: flex;
    align-items: center;
    background: linear-gradient(120deg, #075985, #0e7490);
    color: white;
}

.hero-content {
    max-width: 650px;
}

.hero h1 {
    font-size: 42px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 19px;
    line-height: 1.6;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background: #10b981;
    color: white;
    padding: 15px 25px;
    border-radius: 8px;
    text-decoration: none;
    border: none;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

.btn:hover {
    background: #059669;
}

section {
    padding: 65px 8%;
}

.section-title {
    text-align: center;
    font-size: 30px;
    color: #075985;
    margin-bottom: 35px;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.service-card {
    background: white;
    padding: 30px 20px;
    text-align: center;
    border-radius: 12px;
    box-shadow: 0 3px 15px #00000012;
}

.service-card .emoji {
    font-size: 40px;
    margin-bottom: 15px;
}

.service-card h3 {
    color: #075985;
    margin-bottom: 12px;
}

.service-card p {
    line-height: 1.5;
}

.about {
    background: #e6f4f8;
    line-height: 1.8;
    text-align: center;
}

.about p {
    max-width: 800px;
    margin: auto;
    font-size: 17px;
}

.booking {
    background: white;
}

.form-container {
    max-width: 650px;
    margin: auto;
    background: #f5f9fc;
    padding: 30px;
    border-radius: 12px;
}

.form-container label {
    display: block;
    margin: 15px 0 7px;
    font-weight: bold;
}

.form-container input,
.form-container select,
.form-container textarea {
    width: 100%;
    padding: 13px;
    border: 1px solid #cbd5e1;
    border-radius: 7px;
    font-size: 16px;
}

.form-container textarea {
    resize: vertical;
}

.form-container button {
    width: 100%;
    margin-top: 22px;
}

.contact {
    background: #075985;
    color: white;
    text-align: center;
    line-height: 2;
}

.contact h2 {
    color: white;
}

footer {
    background: #063b56;
    color: white;
    text-align: center;
    padding: 22px;
    font-size: 14px;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #16a34a;
    color: white;
    padding: 15px 20px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 3px 12px #0004;
    z-index: 10;
}

@media(max-width: 600px) {
    header {
        justify-content: center;
        text-align: center;
    }

    nav a {
        display: inline-block;
        margin: 8px;
        font-size: 14px;
    }

    .hero {
        padding: 60px 7%;
    }

    .hero h1 {
        font-size: 32px;
    }

    section {
        padding: 45px 6%;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">💙 Fisio Saúde</div>
    <nav>
        <a href="#inicio">Início</a>
        <a href="#servicos">Serviços</a>
        <a href="#sobre">Sobre</a>
        <a href="#agendamento">Agendamento</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero" id="inicio">
    <div class="hero-content">
        <h1>Movimento é saúde. Qualidade de vida é nosso objetivo!</h1>
        <p>
            Atendimento fisioterapêutico com atenção,
            profissionalismo e cuidado individualizado.
            Cuide do seu corpo e recupere sua qualidade de vida.
        </p>
        <a href="#agendamento" class="btn">
            Agende sua consulta
        </a>
    </div>
</section>

<section id="servicos">
    <h2 class="section-title">Nossos Serviços</h2>

    <div class="services">

        <div class="service-card">
            <div class="emoji">🦴</div>
            <h3>Fisioterapia Ortopédica</h3>
            <p>Reabilitação de lesões musculares,
            articulares e ósseas.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🏃</div>
            <h3>Fisioterapia Esportiva</h3>
            <p>Prevenção e recuperação de lesões
            relacionadas às atividades esportivas.</p>
        </div>

        <div class="service-card">
            <div class="emoji">💪</div>
            <h3>Reabilitação Funcional</h3>
            <p>Exercícios e técnicas para melhorar
            força, mobilidade e funcionalidade.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🧘</div>
            <h3>Tratamento da Dor</h3>
            <p>Atendimento direcionado ao alívio
            da dor e melhora da mobilidade.</p>
        </div>

        <div class="service-card">
            <div class="emoji">❤️</div>
            <h3>Fisioterapia Preventiva</h3>
            <p>Cuidados para prevenir limitações
            e promover saúde e bem-estar.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🏠</div>
            <h3>Atendimento Domiciliar</h3>
            <p>Possibilidade de atendimento
            fisioterapêutico em domicílio.</p>
        </div>

    </div>
</section>

<section class="about" id="sobre">
    <h2 class="section-title">Sobre o Atendimento</h2>
    <p>
        Nosso objetivo é oferecer atendimento fisioterapêutico
        humanizado, buscando a recuperação funcional,
        prevenção de lesões e promoção da qualidade de vida.
        Cada paciente recebe uma avaliação individualizada
        para definição dos objetivos e condutas terapêuticas.
    </p>
</section>

<section class="booking" id="agendamento">
    <h2 class="section-title">Agende sua Consulta</h2>

    <div class="form-container">

        <form id="appointmentForm">

            <label>Nome completo:</label>
            <input type="text" id="nome"
            placeholder="Digite seu nome" required>

            <label>Telefone:</label>
            <input type="tel" id="telefone"
            placeholder="(00) 00000-0000" required>

            <label>Tipo de atendimento:</label>
            <select id="servico" required>
                <option value="">Selecione um serviço</option>
                <option>Fisioterapia Ortopédica</option>
                <option>Fisioterapia Esportiva</option>
                <option>Reabilitação Funcional</option>
                <option>Tratamento da Dor</option>
                <option>Fisioterapia Preventiva</option>
                <option>Atendimento Domiciliar</option>
                <option>Avaliação Fisioterapêutica</option>
            </select>

            <label>Data desejada:</label>
            <input type="date" id="data" required>

            <label>Horário desejado:</label>
            <select id="horario" required>
                <option value="">Selecione o horário</option>
                <option>07:00</option>
                <option>08:00</option>
                <option>09:00</option>
                <option>10:00</option>
                <option>13:00</option>
                <option>14:00</option>
                <option>15:00</option>
                <option>16:00</option>
                <option>17:00</option>
            </select>

            <label>Mensagem (opcional):</label>
            <textarea id="mensagem" rows="4"
            placeholder="Escreva uma mensagem"></textarea>

            <button type="submit" class="btn">
                Solicitar Agendamento pelo WhatsApp
            </button>

        </form>
    </div>
</section>

<section class="contact" id="contato">
    <h2 class="section-title">Entre em Contato</h2>
    <p>📍 Endereço: Informe o endereço da clínica</p>
    <p>📞 Telefone: Informe seu telefone</p>
    <p>📧 E-mail: Informe seu e-mail</p>
    <p>🕒 Atendimento: Segunda a sexta-feira</p>
</section>

<footer>
    <p>© 2026 Fisio Saúde - Todos os direitos reservados.</p>
    <p>Saúde, movimento e qualidade de vida.</p>
</footer>

<a class="whatsapp"
   href="https://wa.me/5565999999999"
   target="_blank" rel="noopener noreferrer">
   WhatsApp
</a>

<script>

// SUBSTITUA PELO SEU NÚMERO COM DDD E CÓDIGO DO PAÍS
const WHATSAPP = "5565999999999";

// Impede agendamento em datas anteriores
const campoData = document.getElementById("data");
const hoje = new Date();
const dataLocal = new Date(
    hoje.getTime() - hoje.getTimezoneOffset() * 60000
).toISOString().split("T")[0];

campoData.min = dataLocal;

document.getElementById("appointmentForm")
.addEventListener("submit", function(event) {

    event.preventDefault();

    const nome = document.getElementById("nome").value;
    const telefone = document.getElementById("telefone").value;
    const servico = document.getElementById("servico").value;
    const data = document.getElementById("data").value;
    const horario = document.getElementById("horario").value;
    const mensagem = document.getElementById("mensagem").value;

    const texto =
`Olá! Gostaria de solicitar um agendamento de fisioterapia.

Nome: ${nome}
Telefone: ${telefone}
Serviço: ${servico}
Data desejada: ${data}
Horário desejado: ${horario}
Mensagem: ${mensagem}

Aguardo a confirmação da disponibilidade.`;

    const url = "https://wa.me/" + WHATSAPP +
        "?text=" + encodeURIComponent(texto);

    window.open(url, "_blank");

});

</script>

</body>
</html>
