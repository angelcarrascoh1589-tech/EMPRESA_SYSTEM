// BOTÓN EXPLORAR

const explorarBtn = document.getElementById("explorarBtn");

explorarBtn.addEventListener("click", function() {

    document.getElementById("destinos").scrollIntoView({
        behavior: "smooth"
    });

});


// BOTÓN INFORMACIÓN

const infoBtn = document.querySelector(".infoBtn");

infoBtn.addEventListener("click", function() {

    alert("¡Bienvenido a Yelapa! Próximamente tendrás más información.");

});