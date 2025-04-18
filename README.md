# nestjs-auth

# Authentification simple avec NestJS (sans guard global)

Ce projet est une implémentation de base d’un système d’authentification avec **NestJS**, inspiré de la [documentation officielle](https://docs.nestjs.com/security/authentication#implementing-the-authentication-guard), sans utiliser de **guard global**.

## Technologies utilisées

- [NestJS](https://nestjs.com/) (framework Node.js)
- TODO: [Passport](https://www.passportjs.org/) (middleware d’authentification)
- TODO: `@nestjs/passport` et `passport-local`
- TODO: `bcrypt` pour le hash de mot de passe
- TODO: `express-session` pour la gestion de session

## Fonctionnalités

- Authentification locale (`/auth/login`)
- TODO: Utilisation de `PassportStrategy` pour valider un utilisateur
- TODO: Session persistante via cookies
- Aucune activation globale du `AuthGuard`, chaque route est protégée manuellement si nécessaire

## Licence 

Ce projet est open-source et peut être utilisé librement pour vos projets d’apprentissage ou de base.