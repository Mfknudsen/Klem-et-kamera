# Klem et kamera
 
Dette repositorie indeholder et script. Dette script er en kopi af Simple Webcam input som jeg har downloaded fra kadenze. Jeg har tilføjet en funtion så den kan modtage output fra Wekinator samtidig med at den selv giver input til Wekinator.
Det output den modtager er en float værdi, som vil være mellem 0 og 1.
Den bruger så denne værdi ganget med 200 og reducere programmets størelse. F.eks. xSize = width - a.

Der er også et Wekinator projekt med i dette repositorie, som indeholder en trænet ai, lavet ud fra træningseksempler. Den er trænet til at man tager begge hænder op foran kameraet og bevæger dem væk eller mod hinanden.