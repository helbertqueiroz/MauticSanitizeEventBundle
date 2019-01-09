# MauticSanitizeEventBundle

Um plugin para Mautic, para ajustar o nome do lead.

## Instalação

Para instalar o plugin, basta fazer o clone do Github dentro da pasta ```plugins```.

```
git clone https://github.com/moskoweb/MauticSanitizeEventBundle.git
```

Depois basta limpar o cache do Mautic e ajustar as permissões:

```
php app/console cache:clear && chmod -R g+rw *
```
