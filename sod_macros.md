# Macros Chasseur

## Gestion du pet

### Appel ou renvoi
```
#showtooltip
/cast [pet] Renvoyer le familier; [nopet] Appel du familier
```

### Ressusciter ou Guérir
```
#showtooltip
/cast [nopet] Ressusciter le familier; [@pet, dead] Ressusciter le familier; [@pet, nodead] Guérison du familier
```


### Nourrir
```
#showtooltip
/cast [nocombat][pet] Nourrir le familier
/use [nocombat][pet] $food

```

### Retour sur perso
```
/petfollow
/petpassive
/cast Célérité
/cast Plongeon
/petautocastoff Célérité
/petautocastoff Plongeon
```
### Retour sur point d'ancrage (précédement défini avec reste aka /petstay)
```
/petpassive
/cast [combat, nohelp] Célérité
/petautocastoff Célérité

```

### Attaque et Ordre de Tuer (il faut parfois spammer plusieurs fois la macro)
```
/petattack [@mouseover, harm][]
/cast Charge
/cast [@mouseover, harm][harm] Célérité
/cast [@mouseover, harm][harm] Plongeon
/cast [@pettarget,exists] Ordre de tuer
```

## Qualité de vie

### Aspects
```
/cancelaura Aspect du guépard
/cast [mod:shift] Aspect du singe; [mod:alt]  Aspect de la vipère; [mod:ctrl] Aspect du faucon; [nomod] Aspect du guépard
```

### Oeil de l'aigle (permet de les enchainer à la suite et de sedéplacer sur toute la carte)
```
#showtooltip
/cleartarget
/cast !Oeil d'aigle
```

### FD
```
#showtooltip Feindre la mort
/stopattack
/stopcasting
/petpassive
/cast Feindre la mort
```


### Melee
```
#showtooltip Attaque du raptor
/stopcasting
/cast Attaque du raptor
/startattack
```

### BURST
```
#showtooltip Tir rapide
/cast Tir rapide
/cast Courroux bestial
/use 14
```

### Tir auto
```
#showtooltip Arc du phénix Solfurie
/cast !Tir automatique
```

### Multi
```
#showtooltip
/targetenemy [noharm]
/cast [@mouseover,harm] Flèches multiples; Flèches multiples
```
### Salve
```
#showtooltip
/cast [@cursor] Salve
```

### Fusée éclairante
```
#showtooltip
/cast [@cursor] Fusée éclairante
```

### Tir des Arcanes
```
#showtooltip Tir des Arcanes
/cast [@mouseover,harm] Tir des Arcanes; Tir des Arcanes
```

### Morsure du serpent
```
#showtooltip
/targetenemy [noexists][dead][help]
/cast [@mouseover,harm] Morsure de serpent; Morsure de serpent
```

### Morsure de la vipère
```
#showtooltip
/targetenemy [noexists][dead][help]
/cast [@mouseover,harm] Morsure de vipère; Morsure de vipère
```

### CC
```
#showtooltip Intimidation
/cast [@mouseover] Intimidation
```
```
#showtooltip
/targetenemy [noharm]
/cast [@mouseover,harm] Trait de choc; Trait de choc
```
```
#showtooltip
/cancelaura Aspect du guépard
/targetenemy [noharm]
/cast Coupure d'ailes
/cast Coupure d'ailes(rang 2)
/cast Coupure d'ailes(rang 1)
/startattack
```

### TRANQ
```
#showtooltip
/stopcasting
/stopcasting
/cast Tir tranquillisant
/cast !Tir automatique
```


### FUFU
```
/cast !Camouflage dans l'ombre
/cast !Rôder
```
