document.addEventListener('DOMContentLoaded', function() {
    console.log('D-Power site loaded');

    // Fonction d'ouverture de modal pour la connexion
    function openLoginModal() {
        alert("Fonctionnalité de connexion à venir !");
    }

    // Gestion de la soumission du formulaire
    const form = document.querySelector('form');

    form.addEventListener('submit', function(event) {
        event.preventDefault(); // Empêche l'envoi réel du formulaire
        alert('Fichier soumis avec succès !');
    });
});
