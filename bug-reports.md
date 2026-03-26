# 🐞 Bug Reports – SauceDemo

---

## 🔴 Bug 1 – Impossible d’ajouter certains produits au panier

**ID :** BUG-001  
**Sévérité :** Élevée  

### Étapes :
1. Se connecter avec `standard_user`
2. Aller sur la liste des produits
3. Cliquer sur "Add to cart" pour certains produits

### Résultat attendu :
Le produit doit être ajouté au panier et le bouton doit passer à "Remove"

### Résultat réel :
Certains produits ne s’ajoutent pas au panier

---

## 🔴 Bug 2 – Bouton "Remove" non fonctionnel

**ID :** BUG-002  
**Sévérité :** Élevée  

### Étapes :
1. Ajouter un produit au panier
2. Cliquer sur "Remove"

### Résultat attendu :
Le produit doit être retiré du panier

### Résultat réel :
Le bouton "Remove" ne fonctionne pas dans certains cas

---

## 🟠 Bug 3 – Absence du prix total dans le panier

**ID :** BUG-003  
**Sévérité :** Moyenne  

### Étapes :
1. Ajouter un ou plusieurs produits au panier
2. Aller dans le panier

### Résultat attendu :
Le prix total des produits doit être affiché

### Résultat réel :
Le prix total n’est pas affiché

---

## 🔴 Bug 4 – Impossible de remplir le champ "Last Name" (Checkout)

**ID :** BUG-004  
**Sévérité :** Critique 🚨  

### Étapes :
1. Se connecter
2. Ajouter un produit au panier
3. Aller au checkout
4. Tenter de remplir le champ "Last Name"

### Résultat attendu :
Le champ "Last Name" doit être modifiable

### Résultat réel :
Le curseur revient automatiquement sur le champ "First Name"
Impossible de remplir "Last Name"

### Impact :
Blocage total du processus de commande

---

## 🟠 Bug 5 – Incohérences visuelles avec l’utilisateur "problem_user"

**ID :** BUG-005  
**Sévérité :** Moyenne  

### Étapes :
1. Se connecter avec `problem_user`
2. Naviguer sur les produits

### Résultat attendu :
Affichage cohérent des éléments visuels

### Résultat réel :
Présence d’anomalies visuelles et incohérences d’affichage

---

## 🟡 Bug 6 – Feedback utilisateur insuffisant (UX)

**ID :** BUG-006  
**Sévérité :** Faible  

### Étapes :
1. Tester les erreurs de connexion
2. Ajouter un produit au panier

### Résultat attendu :
Feedback clair et visible pour guider l’utilisateur

### Résultat réel :
Feedback présent mais manque de visibilité et de clarté

---

## 📊 Conclusion

Plusieurs anomalies critiques et majeures ont été identifiées, notamment :

- blocage du checkout (critique)
- dysfonctionnements du panier
- incohérences visuelles

Ces anomalies impactent directement l’expérience utilisateur et empêchent la finalisation d’une commande.
