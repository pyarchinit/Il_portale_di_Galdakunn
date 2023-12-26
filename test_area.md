function lanciaDado() {
  var risultato = Math.floor(Math.random() * 4) + 1;
  alert("Risultato del dado: " + risultato);
}

// Creazione del pulsante
var pulsanteDado = document.createElement("button");
pulsanteDado.innerHTML = "Lancia il Dado";
pulsanteDado.onclick = lanciaDado;

// Aggiunta del pulsante al corpo del documento
document.body.appendChild(pulsanteDado);
