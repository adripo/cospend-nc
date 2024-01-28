# Nextcloud Cospend 💰

Nextcloud Cospend is een groep/deelbaar budgetmanager. Ik was geinspireerd door het geweldige [IHateMoney](https://github.com/spiral-project/ihatemoney/).

You can use it when you share a house, when you go on vacation with friends, whenever you share expenses with a group of people.

Het laat je projecten aanmaken met deelnemers en rekeningen. Voor iedere deelnemer wordt het saldo berekend op basis van de rekeningen. Balances are not an absolute amount of money at members disposal but rather a relative information showing if a member has spent more for the group than the group has spent for her/him, independently of exactly who spent money for whom. Zo kan je zien wie er nog moet betalen aan de groep of wie er nog moet ontvangen van de groep. Uiteindelijk kunt je vragen om een betalingsplan waarbij je te maken betalingen krijgt om de deelnemersbalans te resetten.

Projectdeelnemers zijn onafhankelijk van Nextcloud gebruikers. Projects can be shared with other Nextcloud users or via public links.

[MoneyBuster](https://gitlab.com/eneiluj/moneybuster) Android client is [te krijgen in F-Droid](https://f-droid.org/packages/net.eneiluj.moneybuster/) en in de [Play store](https://play.google.com/store/apps/details?id=net.eneiluj.moneybuster).

[PayForMe](https://github.com/mayflower/PayForMe) iOS client is currently under developpement!

The private and public APIs are documented using [the Nextcloud OpenAPI extractor](https://github.com/nextcloud/openapi-extractor/). This documentation can be accessed directly in Nextcloud. All you need is to install Cospend (>= v1.6.0) and use the [the OCS API Viewer app](https://apps.nextcloud.com/apps/ocs_api_viewer) to browse the OpenAPI documentation.

## Kenmerken

* ✎ Create/edit/delete projects, members, bills, bill categories, currencies
* ⚖ Check member balances
* 🗠 Display project statistics
* ♻ Display settlement plan
* Move bills from one project to another
* Move bills to trash before actually deleting them
* Archive old projects before deleting them
* 🎇 Automatically create reimbursement bills from settlement plan
* 🗓 Create recurring bills (day/week/month/year)
* 📊 Optionally provide custom amount for each member in new bills
* 🔗 Link personal files to bills (picture of physical receipt for example)
* 👩 Public links for people outside Nextcloud (can be password protected)
* 👫 Share projects with Nextcloud users/groups/circles
* 🖫 Import/export projects as csv (compatible with csv files from IHateMoney and SplitWise)
* 🔗 Generate link/QRCode to easily add projects in MoneyBuster
* 🗲 Implement Nextcloud notifications and activity stream

This app usually support the 2 or 3 last major versions of Nextcloud.

Deze app is werk in uitvoering.

🌍 Help ons deze app te vertalen bij het [Nextcloud-Cospend/MoneyBuster Crowdin project](https://crowdin.com/project/moneybuster).

⚒ Check out other ways to help in the [contribution guidelines](https://github.com/julien-nc/cospend-nc/blob/master/CONTRIBUTING.md).

## Documentation

* [User documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/user.md)
* [Admin documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/admin.md)
* [Developer documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/dev.md)
* [CHANGELOG](https://github.com/julien-nc/cospend-nc/blob/master/CHANGELOG.md#change-log)
* [AUTHORS](https://github.com/julien-nc/cospend-nc/blob/master/AUTHORS.md#authors)

## Bekende problemen

* It does not make you rich

Any feedback will be appreciated.

