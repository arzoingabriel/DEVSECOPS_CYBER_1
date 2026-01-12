# Tableau des Vulnérabilités et Correctifs

| # | Vulnérabilité Référence (CVE/advisory) | Correctif appliqué (commande / version) | Gravité (CVSS / label) | OWASP Top-10 (2021) |
|---|-----------------------------------------|-----------------------------------------|------------------------|---------------------|
| 1 | Injection de commande via template Lodash - CVE-2021-23337 | Modification de `package.json` : `"lodash": "^4.17.21"` puis `npm install`. Version corrigée : 4.17.21 | HIGH | A03:2021 - Injection |
| 2 | ReDoS dans lodash - CVE-2020-28500 | Modification de `package.json` : `"lodash": "^4.17.21"` puis `npm install`. Version corrigée : 4.17.21 | MEDIUM | A03:2021 - Injection |
| 3 | Vérification de signature trop permissive (digestAlgorithm) - CVE-2022-24771 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | HIGH | A02:2021 - Cryptographic Failures |
| 4 | Vérification de signature ne contrôle pas les octets en fin - CVE-2022-24772 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | HIGH | A02:2021 - Cryptographic Failures |
| 5 | Conflit d'interprétation permettant de contourner les vérifications cryptographiques - CVE-2025-12816 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | HIGH | A02:2021 - Cryptographic Failures |
| 6 | Récursion non bornée dans le parsing ASN.1 - CVE-2025-66031 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | HIGH | A04:2021 - Insecure Design |
| 7 | Redirection ouverte (Open Redirect) - CVE-2022-0122 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | MEDIUM | A01:2021 - Broken Access Control |
| 8 | Vérification trop permissive de la structure DigestInfo - CVE-2022-24773 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | MEDIUM | A02:2021 - Cryptographic Failures |
| 9 | Dépassement d'entier permettant de contourner la sécurité basée sur les OID - CVE-2025-66030 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | MEDIUM | A02:2021 - Cryptographic Failures |
| 10 | Pollution de prototype dans l'API de debug - GHSA-5rrq-pxf6-6jx5 | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | LOW | A08:2021 - Software and Data Integrity Failures |
| 11 | Parsing d'URL pouvant mener à un comportement indésirable - GHSA-gf8q-jrpm-jvxq | Modification de `package.json` : `"node-forge": "^1.3.2"` puis `npm install`. Version corrigée : 1.3.2 | LOW | A03:2021 - Injection |
| 12 | Denial of Service via validation insuffisante dans le parsing de tableaux - CVE-2025-15284 | Ajout de `overrides` dans `package.json` : `"overrides": { "qs": "^6.14.1" }` puis `npm install`. Version corrigée : 6.14.1 | HIGH | A04:2021 - Insecure Design |
| 13 | Injection de code arbitraire via deleteFunctions - CVE-2020-7660 | Modification de `package.json` : `"serialize-javascript": "^3.1.0"` puis `npm install`. Version corrigée : 3.1.0 | HIGH | A03:2021 - Injection |
| 14 | XSS via caractères non sécurisés dans les expressions régulières sérialisées - CVE-2019-16769 | Modification de `package.json` : `"serialize-javascript": "^3.1.0"` puis `npm install`. Version corrigée : 3.1.0 | MEDIUM | A03:2021 - Injection |
| 15 | Clé privée SSH committée dans Git - Secret détecté (private-key) | Commande : `git rm --cached private-node.pem.pub`. Mise à jour de `.gitignore` avec patterns `*.pem`, `*.pem.pub`, `*.key`, etc. | HIGH | A07:2021 - Identification and Authentication Failures |
