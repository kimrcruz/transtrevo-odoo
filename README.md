# transtrevo-odoo

Protótipo para validação da arquitectura de dados do CRM e OPS proposta pela KIMIKA para a implementação Odoo da Transtrevo, com o dashboard da actividade de 2026.

Site de uma só página (`index.html`) com menu: Início, Comercial, Operações, Direcção, Arquitectura e Questões em aberto. Fotografia de 09/11/2026, valores em EUR. `dashboard.html` reencaminha para a vista Comercial.

Acesso por código. O conteúdo está cifrado (AES-GCM, chave derivada do código com PBKDF2) e só é decifrado no browser depois de introduzido o código. A fonte em claro não está neste repositório.

Publicado com GitHub Pages a partir da branch `main`, pasta raiz.
