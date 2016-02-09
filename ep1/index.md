---
layout: episode
title: "EP 1 : génération procédurale"
date: vendredi 23 octobre 2015
preview: static/preview-ep1.png
noco: http://noco.tv/emission/23437/nolife/la-faute-a-l-algo/01-chaines-de-markov-et-generation-procedurale
published: true
comments: true
front: true
---

## T-shirts « Keep Calm » générés algorithmiquement

- [Man behind 'Carry On' T-shirts says company is 'dead'](http://money.cnn.com/2013/03/05/smallbusiness/keep-calm-and-carry-on/index.html)
- [Controversial T-shirt destroys business](http://money.cnn.com/2013/06/24/smallbusiness/tshirt-business/index.html?iid=HP_LN)
- [Dictionary + algorithm + PoD t-shirt printer + lucrative meme = rape t-shirts on Amazon](http://iam.peteashton.com/keep-calm-rape-tshirt-amazon/)

## Livres Kindle générés algorithmiquement

- [Patented Book Writing System Creates, Sells Hundreds Of Thousands Of Books On Amazon](http://singularityhub.com/2012/12/13/patented-book-writing-system-lets-one-professor-create-hundreds-of-thousands-of-amazon-books-and-counting/)
- [Philip M. Parker](https://en.wikipedia.org/wiki/Philip_M._Parker) sur Wikipédia
- [Paraphrasing of copyrighted material](https://en.wikipedia.org/wiki/Paraphrasing_of_copyrighted_material)

## Chaînes de Markov

Générer du texte qui n'a aucun sens, c'est [facile](http://kamoulbox.free.fr).

- L'exemple introductif de [Doudou le hamster](https://fr.wikipedia.org/wiki/Chaîne_de_Markov#Exemple_:_Doudou_le_hamster), sur Wikipédia
- [Léa](https://bitbucket.org/piedenis/lea), un package Python pour manipuler des distributions de probabilités discrètes ([slides](https://bitbucket.org/piedenis/lea/raw/5efd5fe01d059000585bfdc5d7b3693cc8942626/images/Lea_FOSDEM15.pdf))

### Applications

- [Mark V. Shaney](https://en.wikipedia.org/wiki/Mark_V._Shaney), un bot IRC qui génère des phrases via chaînes de Markov
- [Subreddit Simulator](https://www.reddit.com/r/SubredditSimulator), un espace de discussion entre bots sur Reddit
- [Un algorithme de composition musicale](http://jill-jenn.net/_static/works/un-algorithme-de-composition-musicale.pdf)
- [JukeDeck.com](https://www.jukedeck.com), un service de génération de musique en ligne et paramétrable

#### Génération d'articles scientifiques

* [Le générateur postmoderne](http://www.elsewhere.org/pomo/)
* [Mathgen](http://thatsmathematics.com/mathgen/) pour les maths
* [SCIgen](http://pdos.csail.mit.edu/scigen/) pour l'informatique

Un article généré par SCIgen [s'est retrouvé accepté à une conférence en 2005](http://pdos.csail.mit.edu/~strib/press.html), et [de nombreux autres ont été acceptés pour publication depuis](http://www.nature.com/news/publishers-withdraw-more-than-120-gibberish-papers-1.14763) !

## Réseaux de neurones récurrents (RNN)

Une autre méthode pour générer du texte (ou des images, ou plein d'autres choses), provenant de l'[apprentissage statistique](https://fr.wikipedia.org/wiki/Apprentissage_automatique). Attention, c'est très technique. Fait remarquable : le texte est produit *lettre par lettre* !

- [Une explication](https://karpathy.github.io/2015/05/21/rnn-effectiveness/) des RNN avec des exemples de textes autogénérés à la manière d'une pièce de Shakespeare, d'un article Wikipédia, d'un article de recherche de géométrie algébrique, d'un code source de programme C…
- [frigo](https://github.com/Alexis211/text_rnn), un bot IRC à base de RNN qui répond à ses interlocuteurs, écrit par [Alex Auvolat](http://adnab.me/) ; voici [quelques exemples](http://adnab.me/notes/frigo/) de conversations produites
- [A Neural Conversational Model](http://arxiv.org/abs/1506.05869), publication par des chercheurs de Google
