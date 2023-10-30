# Innovative Project
In deze applicatie ben ik aan de slag gegaan met ML.net, een open-source machine learning framework voor .NET. In dit document licht ik het volledige ontwikkelingsproces toe, van onderzoek tot implementatie.
### 1. Onderzoek
Ik begon met een diepgaand onderzoek naar ML.net. Door het bestuderen van de documentatie en diverse bronnen, heb ik de kernconcepten van ML.net geleerd. Ook heb ik de beschikbare algoritmen en modellen verkend die ML.net ondersteunt voor verschillende taken.

### 2. Gegevensverzameling en -voorbereiding
Ik heb gekozen voor een dataset met betrekking tot Image Classification. Hierbij heb ik gekozen voor het onderwerp Volleybal. Omdat ik zelf volleybal speel was het opzoeken van foto's een makkelijke opgave. Voor deze opgave leek het mij logisch om hierbij een web-app te maken. Spelers van de sportclub kunnen zich inloggen en foto's uploaden.

### 3. ML-modeltraining
Met ML.net heb ik een voorspellingsmodel getraind met mijn dataset. Gedurende dit proces experimenteerde ik met diverse uitkomsten en parameters. De opmerkelijkste bevinding die ik heb gedaan was als je het model een foto geeft waarvoor je geen specifieke groep hebt gemaakt. Hierbij zal het model dan een groep uitkiezen waarbij deze foto het beste past. Dit was een groot probleem als ik de functionaliteit wou behouden van de web-app. Als oplossing heb ik gekozen voor een "Unwanted" groep. Waarin alle off-topic foto's verschijnen als ze niet voldoen aan de voorwaarden.

### 4. Backend-implementatie
Voor de backend van mijn applicatie heb ik gekozen voor ASP.NET Core. Via EntityFramework kun je op een snelle manier een "basis" Authentication opzetten. De belangrijkste modellen waren: User, File & FileCategory (ML-groepen).

### 5. Frontend-implementatie
De frontend van mijn applicatie is ontwikkeld met ASP.NET Core Web App (MVC). Hierbij heb ik mijn eigen web pagina's ontworpen met pure HTML en CSS.

### 6. Testen en evaluatie
De testen die ik heb uitgevoerd kun je [hier]() terugvinden.  
