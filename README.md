# Kara Modal Box v1.0
[English]
Kara allows to set up a simple modal system (without jQuery), accessible and compatible with keyboard navigation.
[French] 
Kara permet de mettre en place un système de modale simple (sans jQuery), accessible et compatible avec la navigation au clavier.

# Use  
Load Kara's CSS style (before closing the head tag)  
```html
<link rel="stylesheet" href="path/css/kara.css">
```
Chargez le fichier javascript de Kara (avant la fermeture de la balise body)
```html
<script src="path/js/kara.js"></script>
```

#### Simple Modal
Creating a link with the modal1 ID and the js-kara-modal class
```html
<a href="#modal1" class="js-kara-modal">Ouvrir la boite modale</a>
```

#### Modal with Ajax
Creating a link with the modal2 ID and the js-kara-modal class
```html
<a href="modalAjax.html#modal2" class="js-kara-modal">Ouvrir avec Ajax</a>
```

#### Kara and Animate.css
You can safely use the CSS Animate library to go even further in the modal box animation
After loading animate.css, add the animated class followed by the desired animation to modal-wrapper
```html
<div class="modal-wrapper animated swing js-kara-modal-stop">
```
