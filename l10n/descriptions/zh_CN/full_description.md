# Nextcloud Cospend 💰

Nextcloud Cospend 是一款群组/共享支出管理工具。 由伟大的 [IHateMoney](https://github.com/spiral-project/ihatemoney/) 启发。

You can use it when you share a house, when you go on vacation with friends, whenever you share expenses with a group of people.

它可以让您创建带有会员和账单的项目。 每个成员都有根据项目账单计算的余额。 Balances are not an absolute amount of money at members disposal but rather a relative information showing if a member has spent more for the group than the group has spent for her/him, independently of exactly who spent money for whom. 这种方式你可以看到谁欠该群组以及谁欠该群组。 Ultimately you can ask for a settlement plan telling you which payments to make to reset members balances.

Project members are independent from Nextcloud users. Projects can be shared with other Nextcloud users or via public links.

[MoneyBuster](https://gitlab.com/eneiluj/moneybuster) Android client is [available in F-Droid](https://f-droid.org/packages/net.eneiluj.moneybuster/) and on the [Play store](https://play.google.com/store/apps/details?id=net.eneiluj.moneybuster).

[PayForMe](https://github.com/mayflower/PayForMe) iOS client is currently under developpement!

The private and public APIs are documented using [the Nextcloud OpenAPI extractor](https://github.com/nextcloud/openapi-extractor/). This documentation can be accessed directly in Nextcloud. All you need is to install Cospend (>= v1.6.0) and use the [the OCS API Viewer app](https://apps.nextcloud.com/apps/ocs_api_viewer) to browse the OpenAPI documentation.

## 特性

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

This app is under development.

🌍 Help us to translate this app on [Nextcloud-Cospend/MoneyBuster Crowdin project](https://crowdin.com/project/moneybuster).

⚒ Check out other ways to help in the [contribution guidelines](https://github.com/julien-nc/cospend-nc/blob/master/CONTRIBUTING.md).

## Documentation

* [User documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/user.md)
* [Admin documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/admin.md)
* [Developer documentation](https://github.com/julien-nc/cospend-nc/blob/master/docs/dev.md)
* [CHANGELOG](https://github.com/julien-nc/cospend-nc/blob/master/CHANGELOG.md#change-log)
* [AUTHORS](https://github.com/julien-nc/cospend-nc/blob/master/AUTHORS.md#authors)

## 已知问题

* It does not make you rich

Any feedback will be appreciated.

