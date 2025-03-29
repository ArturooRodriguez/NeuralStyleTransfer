# Neural Style Transfer:
"In fine art, especially painting, humans have mastered the skill to create unique visual experiences through composing a complex interplay between the content and style of an image". Da questo concetto è stato sviluppato un sistema artificiale, basato su Deep neural network, in grado di simulare in qualche modo il gesto artistico di un umano e di creare immagini originali di alta qualità. Ciò viene implementato tramite l'utilizzo di due immagini di input, unite tra loro, una da cui viene estrapolato il contenuto e una da cui viene estrapolato lo stile.

Il task in questione prende il nome di Neural style transfer, inventato nel 2015 da Leon Gatys con la pubblicazione [A Neural Algorithm of Artitstic Style](https://arxiv.org/pdf/1508.06576.pdf). L'idea che sta alla base è quella di utilizzare delle reti convoluzionali pre-addestrate per estrarre le caratteristiche stilistiche di un'immagine (immagine di stile) e applicarle ad un'altra (immagine di contenuto).

In questo notebook ci concentriamo sull'implementazione e l'ottimizzazione del NST utilizzando diversi modelli preaddestrati come VGG19, VGG16, MobileNetV2 e ResNet50. Per la valutazione degli output esploriamo diverse metriche per valutare le immagini generate tra cui tra cui i [Global effects](https://www.researchgate.net/publication/350184156_Evaluate_and_improve_the_quality_of_neural_style_transfer) e il PSNR. Il risultato finale, sulla base di questo processo, sarà un'immagine che assomiglia molto all'immagine del contenuto ma che avrà uno stile molto vicino a quello dell'immagine di stile.

## Caratteristiche
- Trasferimento di stile tra immagini con risultati creativi.
- Guida passo passo attraverso un notebook interattivo.
- Possibilità di personalizzare le immagini di input e i parametri dell'algoritmo.
- Utilizzo delle principali librerie di deep learning per un’implementazione efficiente.
