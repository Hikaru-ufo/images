# Zyllio Images

Repository centralisé pour stocker les images et icônes utilisées dans mes plugins Zyllio.

## 📁 Structure

- **icons/** : Icônes des plugins (format recommandé : PNG, 512x512px)
- **screenshots/** : Captures d'écran et démos
- **banners/** : Bannières et visuels promotionnels

## 🔗 Utilisation dans les plugins

### Via GitHub Raw
```
https://raw.githubusercontent.com/Hikaru-ufo/zyllio-images/main/icons/nom-fichier.png
```

### Via jsDelivr CDN (recommandé)
```
https://cdn.jsdelivr.net/gh/Hikaru-ufo/zyllio-images/icons/nom-fichier.png
```

### Avec version spécifique
```
https://cdn.jsdelivr.net/gh/Hikaru-ufo/zyllio-images@v1.0.0/icons/nom-fichier.png
```

## 📝 Exemples d'utilisation

Dans `plugin.json` :
```json
{
  "icon": "https://cdn.jsdelivr.net/gh/Hikaru-ufo/zyllio-images/icons/mon-icone.png"
}
```

## 🎨 Formats recommandés

- **Icônes** : PNG avec fond transparent, 512x512px
- **Screenshots** : PNG ou JPG, max 1920px de largeur
- **Optimisation** : Compresser les images avant upload

## 📦 Versions

- v1.0.0 : Version initiale
