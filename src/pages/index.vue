<template>
  <div class="landing-page">
    <header class="header">
      <h1>OBSERVATORIO COGNITIVO</h1>
    </header>
    <section id="feautures_section" class="features">
      <div class="feature">
        <h2>Investigación</h2>
        <p>Investigamos en neurociencia y psicología cognitiva</p>
      </div>
      <div class="feature">
        <h2>Recursos</h2>
        <p>Producimos datos públicos y los ofrecemos</p>
      </div>
      <div class="feature">
        <h2>Comunidad</h2>
        <p>Trabajamos en la trasferencia de conocimientos</p>
      </div>
    </section>
    <section id="showme_section">
      <p>Descubramos juntos</p>
      <button class="cta-button">Conocé más</button>
    </section>
    <footer class="footer">
      <p>&copy; 2024 Cognitive Observatory. All rights reserved.</p>
    </footer>
  </div>
</template>

<style>
.landing-page {
  font-family: 'Roboto', sans-serif;
  color: #333;
  text-align: center;
  padding: 0 20px;
}

.header {
  background: linear-gradient(135deg, #6200ea, #03dac6);
  color: white;
  padding: 50px 20px;
  margin-bottom: 40px;
}

.header h1 {
  font-size: 3em;
  margin: 0;
}

.header p {
  font-size: 1.2em;
  margin: 20px 0;
}

.cta-button {
  background-color: #03dac6;
  color: white;
  border: none;
  padding: 10px 20px;
  font-size: 1em;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.cta-button:hover {
  background-color: #018786;
}

.features {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-bottom: 40px;
}

.feature {
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 8px;
  margin: 10px;
  width: 30%;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.feature:hover {
  transform: translateY(-10px);
}

.feature h2 {
  color: #6200ea;
  margin-bottom: 10px;
}

#showme_section {
  background: linear-gradient(135deg, #6200ea, #03dac6);
  color: white;
  margin-bottom: 40px;
}

.footer {
  background-color: #6200ea;
  color: white;
  padding: 20px 0;
}

.footer p {
  margin: 0;
}
</style>
