# Reponses au TD

3. npm i -g vercel

4. vercel -v 
donne = 21.1.0

5. vercel init

6. vercel

7. vercel list
ou vercel ls

8. vercel logs https://td-vercel-one.vercel.app

9. vercel inspect [unique-deployment-url]
elle sert à récupérer les informations concernent le déploiement spécifié.

10. Les variables d'environnement permetent d'injecter des valeurs qu'on ne veut pas placer directement dans le code source.

11. vercel env add plain [name] production

12. vercel env ls

13. Les variable d'environnement secrets sont cryptés et sont utilisées pour les informations sensibles comme les mots de passe ou les jetons d'accès.

15. vercel secrets add [secret-name] [secret-value]
puis
vercel env add secret [secret-name] [environment]
et dans la valeur on renseigne le nom du secret.

16. Production, Preview, et Development.

18. vercel-sand-mu.vercel.app

19. Le pull request sert à demander au détenteur du dépôt un merge entre les modification de notre branche et le master. Vercel va déployer les modifictions du pull request dans le preview pour que les tests soient effectués.

20. Vercel passe le déployement en production.

21. L'environnement production correspond à la branche master.

22. 
