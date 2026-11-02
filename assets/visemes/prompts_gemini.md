# Prompts Gemini : bouches (visèmes) de l'hôte

## Mode d'emploi
1. Ouvre Gemini (gemini.google.com), nouvelle conversation, mode image.
2. Joins l'image de l'hôte « neutre, bouche fermée » (dossier de l'hôte dans characters/ sur le Drive, fichier neutre_ferme en 1024 px).
3. Colle d'abord le PROMPT DE BASE, puis un prompt de bouche à la fois, toujours dans la même conversation et toujours à partir de l'image d'origine.
4. Télécharge chaque résultat et nomme-le comme indiqué, puis dépose-le dans le Drive : characters/host/visemes/
5. Si un résultat change le visage, la coiffure ou le cadrage, rejette-le et redemande : « Start again from the original image I uploaded. »

## PROMPT DE BASE (à coller en premier, avec l'image)
```
This is my 3D cartoon character. I need a set of mouth-shape variations for lip-sync animation.
For every image I ask for: keep EXACTLY the same character, same face, same hair, same beard, same skin tone, same eyes, same head size and position, same camera angle, same framing, same lighting, same flat plain background color as the original.
Only change what I ask (the mouth, or the eyebrows, or the head tilt). Square image, 1024x1024. No text, no logo, no watermark.
Reply "ready" and wait for my first request.
```

## Les 8 bouches (un prompt à la fois)
host_neutre_A.png
```
From the original image: mouth wide open, as when saying "AH" in "father". Jaw dropped, tongue resting low, upper teeth slightly visible. Everything else identical.
```
host_neutre_E.png
```
From the original image: mouth stretched wide in a flat smile, as when saying "EE" in "see". Upper and lower teeth visible and close together. Everything else identical.
```
host_neutre_O.png
```
From the original image: lips rounded into an open circle, as when saying "OH" in "go". Medium opening. Everything else identical.
```
host_neutre_OU.png
```
From the original image: lips pushed forward into a small tight round shape, as when saying "OO" in "food" or "W". Small opening. Everything else identical.
```
host_neutre_MBP.png
```
From the original image: lips pressed firmly together, slightly flattened, as when saying "M", "B" or "P". Mouth closed. Everything else identical.
```
host_neutre_FV.png
```
From the original image: upper front teeth resting on the lower lip, as when saying "F" or "V". Everything else identical.
```
host_neutre_L.png
```
From the original image: mouth half open with the tip of the tongue touching the back of the upper teeth, as when saying "L" or "TH". Everything else identical.
```
host_neutre_repos.png
```
From the original image: relaxed mouth, lips very slightly parted, neutral, as at rest between two words. Everything else identical.
```

## Bonus : expressions
host_neutre_sourcils_leves.png
```
From the original image: eyebrows raised high in surprise, mouth closed and neutral. Everything else identical.
```
host_neutre_sourcils_fronces.png
```
From the original image: eyebrows frowned and pulled together, skeptical look, mouth closed and neutral. Everything else identical.
```
host_neutre_tete_gauche.png
```
From the original image: head tilted about 10 degrees to the character's left, same face, mouth closed. Keep the head the same size and centered. Everything else identical.
```
host_neutre_tete_droite.png
```
From the original image: head tilted about 10 degrees to the character's right, same face, mouth closed. Keep the head the same size and centered. Everything else identical.
```

## Ensuite
Quand les 8 bouches sont sur le Drive, préviens-moi. Je fais un test de lip-sync, et si c'est bon, on refait la même série pour les émotions content, surpris et rire, puis pour Vera et Bella.

## VARIANTE : tout sur une seule planche
```
This is my 3D cartoon character. Create ONE single image: a character sheet for lip-sync animation, a grid of 4 columns x 3 rows (12 equal square cells), on a flat plain background of the same color as the original, with thin white gaps between cells.
In every cell: EXACTLY the same character, same face, hair, beard, skin tone, eyes, same head size and position inside the cell, same camera angle and lighting as the original. Only the mouth or expression changes, as listed below. No text, no labels, no numbers, no logo, no watermark.
Row 1: (1) mouth wide open "AH" as in father; (2) wide flat smile with teeth together "EE" as in see; (3) lips rounded, open circle "OH" as in go; (4) lips pushed forward, small tight circle "OO" as in food.
Row 2: (5) lips pressed firmly together "M/B/P"; (6) upper teeth resting on lower lip "F/V"; (7) mouth half open, tongue tip behind upper teeth "L/TH"; (8) relaxed mouth, lips very slightly parted, at rest.
Row 3: (9) eyebrows raised high in surprise, mouth closed; (10) eyebrows frowned, skeptical, mouth closed; (11) head tilted 10 degrees to the character's left, mouth closed; (12) head tilted 10 degrees to the character's right, mouth closed.
Highest resolution possible, ideally 4096 x 3072.
```
