---
layout: default
---

<script>
  // Détection langue navigateur
  const userLang = navigator.language || navigator.userLanguage;

  if (userLang && userLang.toLowerCase().startsWith("fr")) {
    window.location.href = "fr/";
  } else {
    window.location.href = "en/";
  }
</script>

# Redirection en cours...
