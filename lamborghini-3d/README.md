# Lamborghini Aventador SV — Showroom 3D

Page web 100 % autonome (aucun CDN externe) affichant une Lamborghini
Aventador SV photoréaliste (~200 000 triangles, intérieur complet) avec :

- Peinture PBR clearcoat repeignable (8 teintes officielles Lamborghini)
- 3 finitions : brillant, satin, chrome
- 2 ambiances HDR : sunset / studio
- Phares fonctionnels (émissifs + vrais faisceaux), sol miroir, bloom
- 6 presets caméra + orbite/zoom à la souris

## Ouvrir

La page doit être servie par un serveur web (le GLB ne se charge pas en `file://`) :

```bash
cd lamborghini-3d
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

Ou directement en ligne via githack (sans rien installer) :
https://raw.githack.com/louisbidan-tech/agency-ai-automation/claude/3d-lamborghini-model-s9f957/lamborghini-3d/index.html

## Crédits

- Rendu : [three.js](https://threejs.org) r165 (vendorisé dans `vendor/`)
- Modèle 3D : `assets/lambo.glb` (export Blender, source communautaire — usage démo)
- HDRI : Venice Sunset (exemples three.js)
