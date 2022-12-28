---
layout: episode
title: "EP 9 : la surveillance prédictive"
date: vendredi 4 mars 2016
preview: static/preview-ep9.png
published: true
comments: true
---

## Techno-utopianism

**Nous faisons tellement confiance aux technologies pour nous protéger que nous blâmons trop facilement les services de renseignement.**

(cf. Prévention du terrorisme, plus bas)

## Profilage géographique

### Identification de Banksy

Le profilage géographique ([introduction sur OpenClassRooms](https://openclassrooms.com/courses/profilage-geographique)) a gagné en popularité tout récemment, car des chercheurs de Queen Mary University of London l'ont utilisé pour tenter d'**identifier Banksy**.

Ce qui est assez surprenant, c'est qu'ils aient réussi à identifier des points d'intérêt (un pub, l'adresse personnelle de Banksy), à partir d'un **faible échantillon** des positions des œuvres de Banksy (seulement 140).

- Article sur *The Independent* : [*Banksy: Geographic profiling 'proves' artist really is Robin Gunningham, according to scientists*](http://www.independent.co.uk/news/people/banksy-geographic-profiling-proves-artist-really-is-robin-gunningham-according-to-scientists-a6909896.html)
- Un peu plus de détails sur le modèle utilisé ([Dirichlet process mixture model](https://en.wikipedia.org/wiki/Dirichlet_process#Use_in_Dirichlet_mixture_models)) dans *The Economist* : [*Banksy has been tagged, thanks to mathematics*](http://www.economist.com/news/science-and-technology/21693978-analysis-developed-crime-fighting-and-disease-tracking-points-artists)
- L'article scientifique original : [*Tagging Banksy: using geographic profiling to investigate a modern art mystery*](http://www.tandfonline.com/doi/abs/10.1080/14498596.2016.1138246?journalCode=tjss20)

## Prévention de la délinquance

- En 2005, [*Quand Sarkozy voulait détecter les troubles du comportement chez l'enfant*](http://tempsreel.nouvelobs.com/societe/20081201.OBS3496/quand-sarkozy-voulait-detecter-les-troubles-du-comportement-chez-l-enfant.html), L'Obs.
- L'idée a été à nouveau [proposée en 2008 par le porte-parole de l'UMP Frédéric Lefebvre](http://archives-lepost.huffingtonpost.fr/article/2008/12/01/1342749_frederic-lefebvre-veut-detecter-la-delinquance-des-l-age-de-3-ans.html) et en 2010 dans [le rapport Bockel](http://www.lemonde.fr/politique/article/2010/11/03/bockel-remet-son-rapport-sur-la-delinquance-juvenile-au-chef-de-l-etat_1435094_823448.html).

## Prévention du terrorisme

- [*Algorithms and computers won't stop terrorism*](http://www.telegraph.co.uk/news/uknews/terrorism-in-the-uk/11431757/Algorithms-and-computers-wont-stop-terrorism.html), un super article de [Jamie Bartlett](https://en.wikipedia.org/wiki/Jamie_Bartlett_(journalist)) dans *The Telegraph*. 24 février 2016.

> A lawyer representing Aqsa Mahmood – a woman believed to be in Syria at the moment – **criticised the security services** for not having spotted online activity of the three young teenage girls from London who are believed to be en route to Syria via Turkey.

> After a long investigation, the Committee stated that Michael Adebowale, one of Lee Rigby’s two killers, had **communicated his desire to murder a soldier via a social network platform** (later revealed to be Facebook). Facebook had failed to spot this message, so the security services were not alerted.
In response to this revelation, the **Prime Minister** told Parliament that companies such as Facebook need to “have systems in place to spot key words, key phrases and other key things that could be part of **terrorist plotting**”.

Notre citation favorite :

> It is so much easier to ‘predict’ something after the event, to find the key clue, and so incredibly hard to do it beforehand. So when they don’t succeed (and they can’t all the time) we’ll consider them useless. And when they do succeed, we don’t see or hear of it anyway. The result is an intelligence agency that is seen as both omnipresent and incompetent, one that lacks broad public support and can’t do its job.

- Un petit calcul du nombre de faux positifs peut nous faire déchanter sur un algorithme qui fonctionnerait dans 99,5 % des cas : [Avis sur le Projet de loi relatif au Renseignement](http://pablo.rauzy.name/privacy/loirenseignement.html), par Pablo Rauzy, publié dans Mediapart.

> Maintenant, admettons qu'il existe un super algorithme qui fonctionne vraiment très bien, qui donne le bon résultat dans **99.5%** des cas (c'est déjà totalement fantaisiste). Imaginons que sur 65 millions de français il y ait 1000 terroristes. L'algorithme va détecter 1000 × 99.5% = 995 terroristes sur les 1000, mais aussi (65000000 - 1000) × 0.5% = **324995 faux positifs** ! Bien sûr, pour chaque détection, il faudra nécessairement mener une enquête – coûteuse en moyens humains et financiers – pour être sûr que la détection correspond à un vrai terroriste. Sinon, après un attentat, comment expliquer que le terroriste a fait sonner des alarmes mais n'a pas été l'objet d'une surveillance plus poussée ? Les ressources seront donc massivement utilisées pour des faux positifs, ce qui est profondément contre-productif. En plus de cela, il serait gênant d'ignorer le petit nombre de faux négatifs : 5 terroristes non détectés sur 1000, c'est déjà beaucoup !
