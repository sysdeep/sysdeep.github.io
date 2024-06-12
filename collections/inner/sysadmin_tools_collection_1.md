# Вместо бубна: огромная подборка инструментов сисадмина

Оригинал - [Вместо бубна: огромная подборка инструментов сисадмина](https://tproger.ru/digest/sysadmin-compilation)

Хорошему системному администратору нужны хорошие инструменты. Представляем вашему вниманию огромную подборку всего, что может понадобиться для этой работы.

## Резервное копирование

- [Amanda](http://www.amanda.org/) — программа для архивирования информации, обладающая возможностью резервного копирования данных, постоянно хранящихся на множестве компьютеров в компьютерной сети;
- [Attic](https://attic-backup.org/) — программа для дедуплицированного резервного копирования, написанная на Python;
- [Bacula](http://www.bacula.org/) — кроссплатформенное клиент-серверная программа, позволяющая управлять резервным копированием, восстановлением, и проверкой данных по сети для компьютеров и операционных систем различных типов;
- [Bareos](http://www.bareos.org/) — форк инструмента Bacula;
- [Barman](http://www.pgbarman.org/) — менеджер бэкапов для аварийного восстановления серверов PostgreSQL;
- [Backuppc](http://backuppc.sourceforge.net/) — программа для резервного копирования данных с управлением через веб-интерфейс;
- [Brebis](http://brebisproject.org/) — инструмент для автоматической проверки бэкапов;
- [Bup](https://github.com/bup/bup) — эффективная система резервного копирования с глобальной дедупликацией;
- [Burp](http://burp.grke.org/) — программа для резервного копирования и восстановления сети;
- [Duplicati](http://www.duplicati.com/) — бесплатный инструмент для онлайн-хранения зашифрованных бэкапов;
- [Duplicity](http://duplicity.nongnu.org/) — резервное копирование с шифрованием;
- [FreeFileSync](http://www.freefilesync.org/) — инструмент для сравнения и синхронизации папок;
- [Lsyncd](https://github.com/axkibe/lsyncd) — монитор файловой системы, синхронизирующий директории;
- [restic](https://github.com/restic/restic) — быстрая, безопасная и эффективная программа для резервного копирования;
- [Rsnapshot](http://www.rsnapshot.org/) — инструмент для создания снимков файловой системы;
- [SafeKeep](http://safekeep.sourceforge.net/) — open-source приложение для резервного копирования;
- [Snebu](http://www.snebu.com/) – эффективный инструмент для создания резервных копий с помощью снимков системы для Unix/Linux-систем;
- [UrBackup](http://www.urbackup.org/) — простая в использовании система резервного копирования;
- [ZBackup](http://zbackup.org/) — универсальный инструмент для дедупликации бэкапов;
- [Backup](https://github.com/meskyanichi/backup) — библиотека на Ruby для резервного копирования на Unix-системах;
- [DREBS](https://github.com/dojo4/drebs) — инструмент для создания периодических снимков томов AWS EBS.

## Автоматизация сборки

- [Apache Ant](https://ant.apache.org/) — инструмент для автоматизации сборки. Похож на make, написан на Java;
- [Apache Maven](http://maven.apache.org/) — инструмент для автоматизации сборки, в основном для Java;
- [GNU Make](http://www.gnu.org/software/make/) — самый популярный инструмент для автоматизации сборки с множеством применений;
- [Gradle](http://gradle.org/) — ещё один open-source инструмент для автоматизации сборки.

## ChatOps

- [CloudBot](https://github.com/CloudBotIRC/CloudBot) — простой, быстрый, расширяемый open-source IRC-бот на Python;
- [Eggdrop](http://www.eggheads.org/) — самый популярный open-source IRC-бот, гибкий и простой в использовании;
- [Err](http://errbot.net/) — модульный чат-бот, который легко развернуть и поддерживать;
- [Hubot](https://hubot.github.com/) — фреймворк для создания чат-ботов, созданный на основе GitHub Campfire;
- [Lazlo](https://github.com/djosephsen/lazlo) — фреймворк для ChatOps-автоматизации, написанный на Go;
- Lita — чат-бот на Ruby;
- [KeyBase](https://www.keybase.io/) — чат-приложение с шифрованием, облаком и git.

## Клонирование

- [Clonezilla](http://clonezilla.org/) — программа, предназначенная для клонирования дисков и отдельных разделов жёсткого диска, а также создания резервных копий и аварийного восстановления системы;
- [Fog](http://www.fogproject.org/) — open-source система для клонирования;
- [Redo Backup](http://redobackup.org/) — простой, но эффективный инструмент для резервного копирования и восстановления.

## Облачные вычисления

- [AppScale](http://github.com/AppScale/appscale) — облачная платформа для создания масштабируемых веб- и мобильных приложений. Совместима с Google App Engine;
- [CloudStack](http://cloudstack.apache.org/) — open-source платформа облачных вычислений для запуска и управления большими сетями виртуальных машин;
- [Cobbler](http://cobbler.github.io/) — сервер развёртывания Linux;
- [Mesos](http://mesos.apache.org/) — создавайте и запускайте распределённые системы с эффективным использованием ресурсов;
- [OpenNebula](http://opennebula.org/) — облачная платформа для сисадминов и devops;
- [Openshift Origin](https://www.openshift.org/) — дистрибутив Kubernetes для непрерывной разработки приложений и их развёртывания, разработанный Red Hat;
- [OpenStack](https://www.openstack.org/) — open-source программное обеспечение для создания частных и публичных облаков;
- [The Foreman](http://theforeman.org/) — инструмент для управления жизненным циклом физических и виртуальных серверов;
- [Tsuru](http://www.tsuru.io/) — open-source расширяемое PaaS программное обеспечение;
- [Terraform](https://terraform.io/) — позволяет работать с инфраструктурой как с кодом и в основном используется для AWS/GCE.

## Облачная оркестрация

- [BOSH](http://docs.cloudfoundry.org/bosh/) — IaaS платформа оркестрации, изначально созданная для развёртывания и управления Cloud Foundry PaaS, но также полезная для распределённых систем общего назначения;
- [Ansible](http://www.ansible.com/) — содержит модули для управления многими типами облачных ресурсов;
- [Cloudify](http://cloudify.co/) — open-source облачная платформа для оркестрации, написанная на основе TOSCA с помощью Python и YAML;
- [Consul](http://www.consul.io/) — инструмент для настройки сервисов инфраструктуры;
- [Doozerd](https://github.com/ha/doozerd) — высокодоступное хранилище для небольших объёмов чрезвычайно важных данных;
- [etcd](https://github.com/coreos/etcd) — надёжное распределённое хранилище для наиболее критичных данных системы;
- [Juju](https://juju.ubuntu.com/) — развёртывайте, настраивайте и масштабируйте ваше программное обеспечение на публичных и частных облаках;
- MCollective — фреймворк на Ruby для управления серверной оркестрацией;
- [Overcast](http://andrewchilds.github.io/overcast/) — простая программа командной строки, упрощающая развёртывание, настройку и управление кластерами виртуальных машин;
- [Rundeck](http://rundeck.org/) — простой инструмент для оркестрации;
- [Serf](http://www.serfdom.io/) — децентрализованное членство в кластере, обнаружение неполадок и окрестровка;
- [StackStorm](http://stackstorm.com/) — ChatOps-платформа для управления инфраструктурой. Написана на Python;
- [ZooKeeper](http://zookeeper.apache.org/) — сервис для работы с распределёнными системами.

## Облачное хранилище

- [git-annex assistant](http://git-annex.branchable.com/assistant/) синхронизированная папка на всех ваших устройствах под управлением OS X, Linux, Android, а также на съёмных носителях и NAS-устройствах;
- [nextCloud](https://nextcloud.com/) — сетевой доступ к файлам;
- [ownCloud](https://owncloud.org/) — предоставляет универсальный доступ к файлам по сети;
- [Seafile](http://seafile.com/) — open-source решение для облачного хранения;
- SparkleShare — предоставляет услуги по облачному хранению и синхронизации файлов;
- [Swift](http://docs.openstack.org/developer/swift/) — высокодоступное распределённое хранилище;
- [Syncthing](http://syncthing.net/) — open-source система для зашифрованного распределения данных.

## Просмотр кода

- [Gerrit](https://code.google.com/p/gerrit/) — open-source приложение с веб-интерфейсом, интегрируемое с Git, предназначенное для совместного проведения инспекции кода;
- [Phabricator](http://phabricator.org/) — инструмент для просмотра кода, созданный Facebook и используемый WikiMedia, FB, DropBox и другими;
- [Review Board](https://www.reviewboard.org/) — инструмент для совместного просмотра кода с веб-интерфейсом.

## Организация совместной работы

- [Citadel/UX](http://www.citadel.org/) — open-source веб-приложение для организации совместной работы;
- [EGroupware](http://www.egroupware.org/) —  веб-приложение для совместной работы группы людей, написанное на PHP;
- [Horde Groupware](http://www.horde.org/apps/groupware) — веб-приложение на PHP для организации совместной работы;
- [Kolab](https://www.kolab.org/) — свободный почтовый сервер с поддержкой совместной работы, календарей, списков дел, WebDAV, ActiveSync синхронизацией и многим другим;
- [SOGo](https://www.sogo.nu/) — [groupware](https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%D1%81%D0%BE%D0%B2%D0%BC%D0%B5%D1%81%D1%82%D0%BD%D0%BE%D0%B9_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B) — сервер с упором на простоту и масштабируемость;
- [Zimbra](https://www.zimbra.com/) —  программный продукт для автоматизации совместной деятельности рабочих групп.

## База данных управления конфигурации

- [Clusto](https://github.com/clusto/clusto) — инструмент управления кластерами;
- [i-doit](http://www.i-doit.org/) — open-source база данных IT-документации и управления конфигурацией;
- [iTop](https://www.itophub.io/page/about-itop) — настраиваемое [ITSM](https://ru.wikipedia.org/wiki/ITSM)– и CMDB-решение с открытым исходным кодом;
- [Ralph](https://github.com/allegro/ralph) — система управления активами и инфраструктурой датацентров;
- [Sicekit](https://github.com/sicekit/sicekit) — набор инструментов, предназначенных для MediaWiki, чтобы помочь людям, которые поддерживает системы и инфраструктуру.

## Управление конфигурацией

- [Ansible](http://www.ansible.com/) — система управления конфигурациями, написанная на Python;
- [CFEngine](http://cfengine.com/) — фреймворк для управления конфигурацией и её автоматизации;
- [Chef](http://www.opscode.com/chef/) — система управления конфигурациями, написанная на Ruby и Erlang, с использованием предметно-ориентированного языка для описания конфигураций;
- [mgmt](https://github.com/purpleidea/mgmt) — менеджер конфигураций, написанный на Go;
- Pallet — платформа для автоматизации инфраструктуры в облаке, сервере или прямо на виртуальной машине;
- Puppet — кроссплатформенное клиент-серверное приложение, которое позволяет централизованно управлять конфигурацией операционных систем и программ, установленных на нескольких компьютерах. Написано на Ruby;
- [Salt](http://www.saltstack.com/) — система управления конфигурациями и удалённого выполнения операций, написанная на Python.

## Непрерывная интеграция и развёртывание

- [Buildbot](http://buildbot.net/) — open-source фреймворк для автоматизации процессов сборки, тестирования и выпуска программного обеспечения;
- [Drone](https://github.com/drone/drone) — сервер непрерывной интеграции, основанный на Docker и настраиваемый с помощью YAML-файлов;
- [Go](http://www.go.cd/) — open-source сервер непрерывной поставки;
- [Jenkins](http://jenkins-ci.org/) — расширяемый open-source сервер непрерывной интеграции;
- [Spinnaker](http://www.spinnaker.io/) — open-source платформа непрерывной поставки;
- [TeamCity](https://www.jetbrains.com/teamcity/) — мощный инструмент для непрерывной интеграции от JetBrains;

## Панели управления

- [Ajenti](http://ajenti.org/) — панель управления для Linux и BSD;
- [Cockpit](http://cockpit-project.org/) — менеджер Linux-серверов с веб-интерфейсом;
- [Froxlor](http://www.froxlor.org/) — простая в использовании панель для Linux с поддержкой Nginx и PHP-FPM;
- [ISPConfig](http://www.ispconfig.org/) — панель управления хостингом для Linux;
- [Sentora](http://sentora.org/) — панель управления для Linux, BSD и Windows, основанная на ZPanel;
- [VestaCP](http://www.vestacp.com/) — панель управления хостингом для Linux с Nginx;
- [Virtualmin](http://www.virtualmin.com/) — панель управления для Linux, основанная на Webmin;
- [Webmin](http://www.webmin.com/) — панель управления для Linux с веб-интерфейсом.

## Автоматизация развёртывания

- [Capistrano](http://www.capistranorb.com/) — инструмент для автоматизации и развёртывания удалённого сервера, написанный на Ruby;
- [Fabric](http://www.fabfile.org/) — библиотека на Python для удалённого выполнения команд по SSH в целях развёртывания приложения или администрирования системы;
- [Mina](http://nadarei.co/mina/) — быстрый инструмент для развёртывания;
- [Rocketeer](http://rocketeer.autopergamene.eu/) — менеджер задач для автоматического выполнения рутинных операций и инструмент для развёртывания на PHP.

## Создание диаграмм

- [drawthe.net](http://go.drawthe.net/) — динамически рисует диаграмму сети, исходя из текстового описания.

## Распределённые файловые системы

- [Ceph](http://ceph.com/) — open-source объектная сеть хранения, обеспечивающая как файловый, так и блочный интерфейсы доступа;
- [LeoFS](http://leo-project.net/) — высокодоступная, распределённая, отказоустойчивая файловая система;
- [GlusterFS](http://www.gluster.org/) — распределённая, параллельная, линейно масштабируемая файловая система с возможностью защиты от сбоев;
- [HDFS](http://hadoop.apache.org/) — файловая система, предназначенная для хранения файлов больших размеров, поблочно распределённых между узлами вычислительного кластера. Написана на Java для фреймворка Hadoop;
- [Lustre](http://lustre.opensfs.org/) — распределённая файловая система массового параллелизма, обычно используемая для крупномасштабных кластерных вычислений;
- [MooseFS](http://www.moosefs.org/) — отказоустойчивая, распределенная сетевая файловая система с открытым исходным кодом;
- [OpenAFS](http://www.openafs.org/) — распределённая файловая система с поддержкой нескольких ОС;
- [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) — open-source децентрализованная облачная файловая система;
- [XtreemFS](http://www.xtreemfs.org/) — отказоустойчивая распределённая файловая система.

## DNS

- [Bind](https://www.isc.org/downloads/bind/) — открытая и наиболее распространённая реализация DNS-сервера;
- [djbdns](http://cr.yp.to/djbdns.html) — простой и безопасный набор программ для обслуживания и разрешения DNS-зон;
- [Designate](https://wiki.openstack.org/wiki/Designate) — DNS REST API с поддержкой нескольких DNS-серверов в качестве бэкенда;
- [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) — легковесный и быстроконфигурируемый DNS-, DHCP- и TFTP-сервер, предназначенный для обеспечения доменными именами и связанными с ними сервисами небольших сетей;
- [Knot](https://www.knot-dns.cz/) — высокопроизводительный open-source авторитетный DNS-сервер;
- [NSD](http://www.nlnetlabs.nl/projects/nsd/) — авторитетный DNS-сервер на Си;
- [PowerDNS](https://www.powerdns.com/) — высокопроизводительный DNS-сервер с множеством функций для балансировки нагрузки, написанный на C++;
- [Unbound](http://unbound.net/) — рекурсивный и кэширующий DNS-преобразователь;
- Yadifa — легковесный авторитетный DNS-сервер с возможностями DNSSEC.

## Редакторы

- [Atom](https://atom.io/) — текстовый редактор от GitHub;
- [Brackets](http://brackets.io/)  — open-source текстовый редактор для веб-дизайнеров и фронтенд-разработчиков;
- [Eclipse](http://eclipse.org/) — IDE с системой расширений, написанная на Java;
- [Geany](http://www.geany.org/) — текстовый редактор, использующий GTK+;
- [GNU Emacs](http://www.gnu.org/software/emacs/) — расширяемый и настраиваемый текстовый редактор;
- [Haroopad](http://pad.haroopress.com/) — редактор разметки с возможностью сразу же видеть результат;
- ICEcoder —  редактор кода с веб-интерфейсом;
- [Intellij IDEA](https://github.com/JetBrains/intellij-community) — мощная IDE с множеством плагинов, написанная на Java и Kotlin;
- [jotgit](https://github.com/jdleesmiller/jotgit) — редактор для совместного редактирования;
- [Light Table](http://www.lighttable.com/) — open-source редактор кода с системой расширений;
- Lime — open-source альтернатива Sublime Text, написанная на Go;
- [SciTE](http://www.scintilla.org/SciTE.html) — текстовый редактор на основе SCIntilla;
- [TextMate](https://github.com/textmate/textmate/) — текстовый редактор для OS X.
- [Vim](http://www.vim.org/) — текстовый редактор с широкими возможностями для настройки;
- [Visual Studio Code](https://code.visualstudio.com/) — настраиваемый, кроссплатформенный редактор кода от Microsoft.

## Управление IT-активами

- [GLPI](http://glpi-project.org/) — система работы с заявками и инцидентами, а также для инвентаризации компьютерного оборудования;
- [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) — позволяет пользователям инвентаризировать IT-активы;
- [Netbox](https://github.com/digitalocean/netbox) — инструмент для управления IP-адресами и инфраструктурой датацентра;
- [RackTables](http://racktables.org/) — система управления активами для датацентров;
- [Ralph](https://github.com/allegro/ralph) — система управления активами и инфраструктурой датацентров;
- [Snipe IT](http://snipeitapp.com/) — система управления активами и лицензиями;
- [OpenDCIM](http://www.opendcim.org/) — приложение для управления инфраструктурой датацентра.

## LDAP

- [389 Directory Server](http://port389.org/) — LDAP-сервер, разработанный Red Hat;
- [Apache Directory Server](http://directory.apache.org/) — проект Apache Software Foundation, написанный на Java;
- [OpenLDAP](http://openldap.org/) — open-source реализация LDAP;
- [Apache Directory Studio](https://directory.apache.org/studio/) — LDAP-клиент, основанный на Eclipse.

## Работа с логами

- [Echofish](http://www.echothrust.com/projects/echofish) — система для сбора и анализа логов в реальном времени;
- [Fluentd](http://www.fluentd.org/) — open-source система для сбора логов;
- [Flume](https://flume.apache.org/) — распределённая система сбора и агрегации логов;
- [Graylog2](http://graylog2.org/) — сервер для анализа событий и логов с возможностями оповещения;
- [Heka](http://hekad.readthedocs.org/en/latest/) — система для работы с логами от Mozilla;
- [Kibana](http://www.elasticsearch.org/overview/kibana/) — инструмент для визуализации данных;
- [Logstash](http://logstash.net/) — инструмент для управления событиями и логами;
- [Octopussy](http://www.octopussy.pm/) — open-source решение для работы с логами.

## Почтовые серверы

- [Cyrus IMAP/POP3](http://cyrusimap.org/) — open-source почтовый сервер, который предназначен для запуска на закрытых серверах;
- [Dovecot](http://www.dovecot.org/) — IMAP- и POP3-сервер, разрабатываемый с упором на безопасность, гибкость настройки и быстродействие;
- [Exim](http://www.exim.org/) — агент пересылки сообщений для Unix-систем;
- [Haraka](http://haraka.github.io/) — высокопроизводительный SMTP-сервер на JavaScript;
- [MailCatcher](http://mailcatcher.me/) — простой SMTP-сервер на Ruby. Полезен в целях разработки или отладки;
- [Maildrop](https://github.com/m242/maildrop) — высокопроизводительный open-source SMTP-сервер;
- [OpenSMTPD](https://opensmtpd.org/) — защищённый SMTP-сервер;
- [Postfix](http://www.postfix.org/) — open-source агент передачи почты;
- [Qmail](http://cr.yp.to/qmail.html) — безопасная замена Sendmail;
- [Sendmail](http://www.sendmail.com/sm/open_source/) — один из старейших агентов передачи почты.
- [Mail-in-a-Box](https://mailinabox.email/) — легкоразвёртываемый почтовый сервер;
- [iRedMail](http://www.iredmail.org/) — open-source почтовый сервер, основанный на Postfix и Dovecot.

## Обмен сообщениями

- [ejabberd](http://www.ejabberd.im/) — распределённый и устойчивый к отказам XMPP-сервер, написанный в основном на Erlang;
- [Metronome IM](https://metronome.im/) — XMPP-сервер мгновенного обмена сообщениями, начинался как форк Prosody IM;
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) — масштабируемая платформа для мгновенного обмена сообщениями, написанная на Erlang;
- [Openfire](http://www.igniterealtime.org/projects/openfire/) — кроссплатформенный XMPP-сервер, написанный на Java;
- [Prosody IM](http://prosody.im/) — кроссплатформенный XMPP-сервер, написанный на Lua;
- Tigase — XMPP-сервер на Java;
- [Candy](http://candy-chat.github.io/candy/) – многопользовательский XMPP-клиент, написанный на JavaScript;
- [Kaiwa](http://getkaiwa.com/) — open-source веб-клиент для XMPP;
- [Lets-Chat](http://sdelements.github.io/lets-chat/) — чат на Node.js с собственным сервером.

## Мониторинг

- [Alerta](https://github.com/guardian/alerta) — распределённая, масштабируемая и гибкая система мониторинга;
- [Canopsis](http://www.canopsis.org/) — open-source гипервизор;
- [Cacti](http://www.cacti.net/) — инструмент с веб-интерфейсом, который собирает статистические данные за определённые временные интервалы и позволяет отобразить их в графическом виде;
- [Cabot](http://cabotapp.com/) — легко развёртываемая служба мониторинга и оповещений на собственном сервере;
- [Centreon](http://www.centreon.com/) — open-source инструмент для мониторинга производительности;
- check_mk — набор расширений для Nagios;
- [Flapjack](http://flapjack.io/) — система мониторинга маршрутизации уведомлений;
- Icinga — форк Nagios;
- [LibreNMS](https://github.com/librenms/librenms/) — форк Observium;
- [Monit](http://mmonit.com/monit/#home) — небольшой open-source инструмент для управления и мониторинга Unix-систем;
- [Munin](http://munin-monitoring.org/) — сетевой инструмент мониторинга ресурсов;
- [Naemon](http://www.naemon.org/) — сетевой инструмент для мониторинга, основанный на Nagios, но с улучшениями производительности и новой функциональностью;
- [Nagios](http://www.nagios.org/) — open-source инструмент для мониторинга компьютерных систем и сетей: наблюдения, контроля состояния вычислительных узлов и служб, оповещения администратора в том случае, если какие-то из служб прекращают свою работу;
- [Observium](http://www.observium.org/) — система мониторинга для Cisco, Windows, Linux, HP, Juniper, Dell, FreeBSD, Brocade, Netscaler, NetApp и многих других. Есть платная и бесплатная версии;
- [Opsview](http://www.opsview.com/solutions/core) — система мониторинга, основанная на Nagios 4;
- [Riemann](http://riemann.io/) — гибкая система мониторинга распределённых систем;
- Sensu — open-source фреймворк для мониторинга на Ruby;
- [Sentry](https://getsentry.com/) — инструмент для мониторинга приложений и логирования событий;
- [Serverstats](https://sourceforge.net/projects/serverstats.berlios/) – простой инструмент для создания графиков с помощью rrdtool;
- [Seyren](https://github.com/scobal/seyren) — дашборд с оповещениями для Graphite;
- [Shinken](http://www.shinken-monitoring.org/) — open-source фреймворк для мониторинга на Python;
- [Zabbix](http://www.zabbix.com/) — open-source система мониторинга и отслеживания статусов разнообразных сервисов компьютерной сети, серверов и сетевого оборудования;
- [Adagios](http://adagios.org/) — веб-интерфейс для конфигурации Nagios;
- [Dash](https://github.com/afaqurk/linux-dash) — веб-дашборд для Linux;
- [Thruk](http://www.thruk.org/) — веб-интерфейс для Naemon, Nagios, Icinga и Shinken;
- [Uchiwa](https://uchiwa.io/) — open-source дашборд для Sensu;
- OMD — система сетевого мониторинга.

## Показатели и сбор показателей

- [Collectd](http://collectd.org/) — демон для сбора системной статистики;
- [Collectl](http://collectl.sourceforge.net/) — высокоточный инструмент для сбора показателей производительности системы;
- [Smashing](https://github.com/Smashing/smashing) — фреймворк на Ruby, позволяющий создавать дашборды. Является форком [Dashing](https://github.com/Shopify/dashing);
- [Diamond](https://github.com/python-diamond/Diamond) — демон на Python, собирающий статистику;
- [Facette](http://facette.io/) — инструмент для визуализации временных данных, написанный на Go;
- [Freeboard](https://github.com/Freeboard/freeboard) — open-source инструмент для создания дашбордов;
- [Ganglia](http://ganglia.sourceforge.net/) — масштабируемая распределённая система мониторинга для высокопроизводительных систем;
- [Grafana](http://grafana.org/) — open-source программное обеспечение для анализа временных рядов;
- [Graphite](http://graphite.readthedocs.org/en/latest/) — open-source инструмент для хранения временных данных и их отображения;
- [InfluxDB](http://influxdb.com/) — open-source распределённая база данных для хранения временных рядов;
- [KairosDB](https://github.com/kairosdb/kairosdb) — база данных для хранения временных рядов, является форком OpenTSDB 1.x;
- [NetData](http://my-netdata.io/) — система для распределённого мониторинга производительности и работоспособности в реальном времени;
- [OpenTSDB](http://opentsdb.net/) — масштабируемая, распределённая open-source база данных для хранения временных рядов;
- [Packetbeat](https://www.elastic.co/products/beats/packetbeat) — захватывает сетевой трафик о отображает его на дашборде Kibana;
- [Prometheus](http://prometheus.io/) — система мониторинга сервисов и база данных временных рядов;
- [RRDtool](http://oss.oetiker.ch/rrdtool/) — набор утилит для хранения, обработки и визуализации динамических последовательностей данных;
- [Statsd](https://github.com/etsy/statsd/) —  демон на Node.js для сбора статистики.

## Управление конфигурацией сети

- [GestióIP](http://www.gestioip.net/) — open-source решение для управления IP-адресами;
- [NOC Project](http://nocproject.org/) — масштабируемая, высокопроизводительная open-source [система эксплуатационной поддержки](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%8D%D0%BA%D1%81%D0%BF%D0%BB%D1%83%D0%B0%D1%82%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%BE%D0%B9_%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B8);
- [Netbox](https://github.com/digitalocean/netbox) — инструмент для управления IP-адресами и инфраструктурой датацентра;
- [Oxidized](https://github.com/ytti/oxidized) — инструмент с веб-интерфейсом для резервного копирования конфигурации сетевых устройств;
- [phpIPAM](http://phpipam.net/) — open-source инструмент для управления IP-адресами. Имеет интеграцию с [PowerDNS](https://www.powerdns.com/);
- [RANCID](http://www.shrubbery.net/rancid/) — отслеживает конфигурацию сетевого устройства и ведёт журнал изменений;
- [rConfig](http://www.rconfig.com/) — open-source инструмент для управления конфигурацией сетевых устройств;
- [trigger](https://github.com/trigger/trigger) — надёжный инструмент для автоматизации настройки сети, написанный на Python.

## Рассылки

- [DadaMail](http://dadamailproject.com/) — приложение для рассылок, написанное на Perl;
- [phpList](http://www.phplist.com/) — приложение для рассылок с бесплатным тарифом на 300 сообщений в месяц.

## NoSQL

- [Apache HBase](http://hbase.apache.org/)— open-source нереляционная распределённая база данных;
- [Cassandra](http://cassandra.apache.org/) — распределённая система управления базами данных, рассчитанная на создание высокомасштабируемых и надёжных хранилищ огромных массивов данных;
- [Hypertable](http://hypertable.org/) — высокопроизводительная, масштабируемая база данных по образцу BigTable;
- [CouchDB](http://couchdb.apache.org/) — документо-ориентированная система управления базами данных с открытым исходным кодом, не требующая описания схемы данных;
- [ElasticSearch](http://www.elasticsearch.org/) — база данных, написанная на Java;
- [MongoDB](http://www.mongodb.org/) — документоориентированная система управления базами данных с открытым исходным кодом, не требующая описания схемы таблиц;
- [RavenDB](http://ravendb.net/) — полностью транзакционная документоориентированная база данных;
- [RethinkDB](http://www.rethinkdb.com/) — распределённая документоориентированная СУБД с открытым исходным кодом, сохраняющая данные в бессхемном JSON-формате;
- [FlockDB](https://github.com/twitter/flockdb) — распределённая, отказоустойчивая графовая база данных от Twitter;
- [Neo4j](http://www.neo4j.org/) — open-source графовая база данных;
- [LevelDB](https://github.com/google/leveldb) – высокоэффективная база данных типа «ключ-значение» от Google;
- [Redis](http://redis.io/) — нереляционная высокопроизводительная СУБД;
- [Riak](http://basho.com/riak/) — распределённая open-source NoSQL-СУБД типа «ключ-значение».

## Упаковка

- [fpm](https://github.com/jordansissel/fpm) — эффективный упаковщик для множества платформ;
- [omnibus-ruby](https://github.com/opscode/omnibus-ruby) — упаковщик на Ruby;
- [packman](http://packman.readthedocs.org/) — open-source упаковщик на Python;
- [tito](https://github.com/dgoodwin/tito) — создаёт RPM для проектов на основе git.

## Распределение и планирование задач

- [ActiveMQ](http://activemq.apache.org/) — open-source брокер сообщений написанный на Java. Имеет полную поддержку JMS;
- [BeanstalkD](http://kr.github.io/beanstalkd/) — простая и быстрая очередь задач;
- [Gearman](http://gearman.org/) — фреймворк для распределения задач;
- [Kafka](http://kafka.apache.org/) — распределённый брокер сообщений;
- [RabbitMQ](http://www.rabbitmq.com/) — платформа, реализующая систему обмена сообщениями между компонентами программной системы на основе стандарта AMQP;
- [NSQ](http://nsq.io/) — распределённый брокер сообщений;
- [ZeroMQ](http://zeromq.org/) — высокопроизводительная асинхронная библиотека обмена сообщениями.

## СУБД

- [Firebird](http://www.firebirdsql.org/) — универсальная open-source база данных;
- [Galera](http://galeracluster.com/) — масштабируемый кластер для MySQL;
- [MariaDB](https://mariadb.org/) — форк MySQL, разработанный сообществом;
- [MySQL](http://dev.mysql.com/) — популярная реляционная СУБД;
- [Percona Server](http://www.percona.com/software) — улучшенная замена MySQL;
- [PostgreSQL](http://www.postgresql.org/) — ещё одна популярная open-source реляционная база данных;
- [PostgreSQL-XL](http://www.postgres-xl.org/) — open-source масштабируемый кластер баз данных на основе PostgreSQL;
- [SQLite](http://sqlite.org/) — библиотека с автономной, безсерверной, транзакционной базой данных.

## Безопасность

- [Blackbox](https://github.com/StackExchange/blackbox) — безопасное хранение данных в Git/Mercurial;
- [Denyhosts](http://denyhosts.sourceforge.net/) — средство против брутфорс-атак на SSH-сервер;
- [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) — сканирует логи и выполняет определённые действия для подозрительных IP-адресов;
- [fwknop](https://www.cipherdyne.org/fwknop/) — защищает порты с помощью SPA-авторизации;
- [Glastopf](http://glastopf.org/) — ханипот для эмуляции уязвимостей и сбора информации о атакующих;
- [Kippo](https://github.com/desaster/kippo) — ханипот для логирования брутфорс-атак;
- [OSSEC](http://ossec.net/) — хостовая система обнаружения вторжений, которая проводит анализ логов, обнаруживает руткиты и многое другое;
- [OSQuery](https://osquery.io/) — обращайтесь к вашим устройствам как к базе данных с помощью базовых SQL-команд;
- [pfSense](https://www.pfsense.org/) — дистрибутив для создания межсетевого экрана/маршрутизатора, основанный на FreeBSD;
- Snort — open-source система предотвращения и обнаружения вторжений;
- [SpamAssassin](https://spamassassin.apache.org/) — мощный спам-фильтр с множеством методик обнаружения;
- [BounCA](https://bounca.org/) — веб-инструмент для генерации самоподписанных SSL-сертификатов.

## Обнаружение сервисов

- [Consul](http://www.consul.io/) — инструмент для обнаружения, мониторинга и настройки сервисов;
- [Doozerd](https://github.com/ha/doozerd) — высокодоступное хранилище для небольших объёмов чрезвычайно важных данных;
- [ZooKeeper](http://zookeeper.apache.org/) — сервис для работы с распределёнными системами.

## Контейнеры

- [Bitnami](https://bitnami.com/) — сервис для автоматической упаковки, развёртывания и поддержки веб-приложений;
- [Docker](http://www.docker.com/) — программное обеспечение для автоматизации развёртывания и управления приложениями в среде виртуализации на уровне операционной системы;
- [LXC](https://linuxcontainers.org/lxc/) — система виртуализации на уровне операционной системы для запуска нескольких изолированных экземпляров операционной системы Linux на одном узле;
- [LXD](https://linuxcontainers.org/lxd/) — менеджер контейнеров;
- [OpenVZ](http://openvz.org/) — реализация технологии виртуализации на уровне операционной системы, которая базируется на ядре Linux;
- [Docker Compose](https://docs.docker.com/compose/) — инструмент для определения и запуска многоконтейнерных Docker-приложений;
- [Singularity](http://singularity.lbl.gov/) — контейнеры приложений для Linux.

## SSH

- [Advanced SSH config](https://pypi.python.org/pypi/advanced-ssh-config/) — расширяет возможности файла ssh_config;
- [autossh](http://www.harding.motd.ca/autossh/) — автоматически возобновляет ssh-сессию после прерывания сети;
- [Cluster SSH](http://sourceforge.net/projects/clusterssh/) — контроль над многими окнами xterm с помощью простой консоли;
- [DSH](http://www.netfort.gr.jp/~dancer/software/dsh.html.en) — обёртка для выполнения нескольких удалённых shell-команд из одной командной строки;
- [Mosh](http://mosh.mit.edu/) — мобильный shell;
- [parallel-ssh](https://github.com/ParallelSSH/parallel-ssh) — запускайте SSH-команды асинхронно на множестве серверов с минимальной нагрузкой;
- [pdsh](https://code.google.com/p/pdsh/) — многопоточный shell-клиент, параллельно выполняющий команды на множестве удалённых хостов;
- [SSH Power Tool](http://code.google.com/p/sshpt/) — выполняйте команды и загружайте файлы на несколько серверов одновременно без использования pre-shared ключей;
- sshrc — сохраняет ~/.sshrc на локальном компьютере после удалённого подключения;
- [stormssh](http://stormssh.readthedocs.org/) — инструмент командной строки для управления SSH-соединениями.

## Статистика

- [Analog](http://www.web42.com/analog/) — анализатор лог-файлов;
- [AWStats](http://www.awstats.org/) — бесплатный генератор графической статистики;
- [GoAccess](http://goaccess.io/) — анализ логов в реальном времени и интерактивный просмотр в терминале;
- [Open Web Analytics](http://www.openwebanalytics.com/) — добавляйте веб-аналитику на сайты с помощью JavaScript, PHP или REST API;
- Webalizer — бесплатная программа для анализа логов сервера.

## Страницы состояния

- [Cachet](https://cachethq.io/) — open-source система страниц состояния на PHP.

## Тикет-системы

- [Bugzilla](http://www.bugzilla.org/) — багтрекер общего назначения, изначально созданный Mozilla для внутренних нужд;
- [Flyspray](http://flyspray.org/) — багтрекер с веб-интерфейсом, написанный на PHP;
- [MantisBT](http://www.mantisbt.org/) — open-source багтрекер с веб-интерфейсом;
- [osTicket](http://osticket.com/) — простая тикет-система для техподдержки;
- [OTRS](http://www.otrs.com/) — открытая система обработки заявок;
- [Redmine](http://www.redmine.org/) — open-source тикет-система, написанная на Ruby;
- [Request Tracker](http://www.bestpractical.com/rt/) — тикет-система на Perl;
- [TheBugGenie](http://www.thebuggenie.com/) — бесплатная для небольших команд тикет-система.

## Устранение неполадок и диагностика

- [mitmproxy](http://mitmproxy.org/) — инструмент на Python для перехвата, просмотра и изменения сетевого трафика;
- [Sysdig](http://www.sysdig.org/) — анализируйте контейнеры и оркестраторы в реальном времени или захватывайте активность контейнера для дальнейшего анализа;
- [Wireshark](http://www.wireshark.org/) — популярная программа-анализатор трафика;
- [Trinity Rescue Kit](http://trinityhome.org/) — Linux Live CD для восстановления машин на Linux и Windows.

## Управление проектами

- [GitBucket](https://github.com/takezoe/gitbucket) — клон GitHub, написанный на Scala;
- [GitLab](https://www.gitlab.com/) — клон GitHub, написанный на Ruby;
- [Gogs](http://gogs.io/) — легковесный Git-сервис, написанный на Go;
- [Phabricator](http://phabricator.org/) — инструмент для просмотра кода, созданный Facebook и используемый WikiMedia, FB, DropBox и другими;
- [Redmine](http://www.redmine.org/) — open-source серверное веб-приложение для управления проектами и задачами, написанное на Ruby;
- [Taiga](https://taiga.io/) — open-source инструмент для управления проектами на основе методик Kanban и Scrum;
- [The Bug Genie](http://www.thebuggenie.com/) — инструмент на PHP для управления проектами и отслеживания задач;
- [Trac](http://trac.edgewall.org/) — средство управления проектами и отслеживания ошибок в программном обеспечении, написанное на Python.

## Управление версиями

- [Fossil](http://www.fossil-scm.org/) — система управление версиями со встроенной wiki и багтрекером;
- [Git](http://git-scm.com/) — распределённая система управления версиями с акцентом на скорость;
- [GNU Bazaar](http://bazaar.canonical.com/) — распределённая система управления версиями, спонсируемая Canonical;
- [Mercurial](http://mercurial.selenic.com/) — кроссплатформенная распределённая система управления версиями, разработанная для эффективной работы с очень большими репозиториями кода;
- [Subversion](http://subversion.apache.org/) — open-source централизованная система управления версиями.

## Виртуализация

- Archipel — платформа для управления виртуальными машинами, использующая XMPP;
- [KVM](http://www.linux-kvm.org/) — виртуализация для Linux;
- [OpenNebula](http://opennebula.org/) — облачная платформа для сисадминов и devops;
- [oVirt](http://www.ovirt.org/) — open-source платформа для виртуализации, основанная на KVM;
- [Packer](http://www.packer.io/) — инструмент для создания идентичных образов машин для нескольких платформ;
- [Proxmox VE](https://www.proxmox.com/proxmox-ve) — open-source платформа для виртуализации;
- [QEMU](http://www.qemu.org/) — open-source программа для эмуляции аппаратного обеспечения различных платформ и виртуализации;
- [Vagrant](https://www.vagrantup.com/) — инструмент  для создания и конфигурирования виртуальной среды разработки;
- [VirtualBox](https://www.virtualbox.org/) — виртуализация для Windows, Linux, FreeBSD, macOS, Solaris/OpenSolaris, ReactOS, DOS и других;
- [Xen](http://www.xenproject.org/) — кроссплатформенный гипервизор, распространяемый по лицензии GPL.

## VPN

- [OpenVPN](https://community.openvpn.net/) — применяет специальный протокол безопасности, который использует SSL/TLS для обмена ключами;
- [Pritunl](http://pritunl.com/) — VPN-решение, основанное на OpenVPN;
- [SoftEther](https://www.softether.org/) — многопротокольный VPN с расширенными функциями;
- [sshuttle](https://github.com/sshuttle/sshuttle) — прозрачный прокси-сервер, который работает как VPN;
- [strongSwan](http://www.strongswan.org/) — open-source VPN для Linux;
- [tinc](http://www.tinc-vpn.org/) — распределённый p2p VPN;
- [wireguard](https://www.wireguard.com/) — быстрый и защищённый VPN.

## Веб

- [Apache](http://httpd.apache.org/) — самый популярный веб-сервер;
- [Caddy](https://caddyserver.com/) — HTTP/2 веб-сервер с автоматическим HTTPS:
- [Cherokee](http://cherokee-project.com/) — легковесный и высокопроизводительный веб-сервер;
- [Lighttpd](http://www.lighttpd.net/) — веб-сервер, оптимизированный для случаев, когда критически важна скорость;
- [Nginx](http://nginx.org/) — HTTP-сервер и обратный прокси-сервер, почтовый прокси-сервер, а также TCP/UDP прокси-сервер общего назначения;
- [uWSGI](https://github.com/unbit/uwsgi/) — веб-сервер и сервер веб-приложений, первоначально реализованный для запуска Python-приложений через протокол WSGI;
- [HAProxy](http://www.haproxy.org/) — надёжный TCP/HTTP балансировщик нагрузки;
- [Squid](http://www.squid-cache.org/) — кэширующий прокси для HTTP, HTTPS, FTP и не только;
- [Traefik](https://traefik.io/) — обратный прокси и балансировщик нагрузки, написанный на Go;
- [Varnish](https://www.varnish-cache.org/) — обратный HTTP-прокси.

## Веб-почта

- [Mailpile](https://www.mailpile.is/) — почтовый клиент с упором на предоставление пользователям шифрования и конфиденциальности по умолчанию;
- [Roundcube](http://roundcube.net/) — клиент для веб-почты с веб-интерфейсом, написанный на PHP;
- [SquirrelMail](http://squirrelmail.org/) — клиент для веб-почты на PHP.

## Вики

- [BookStack](https://www.bookstackapp.com/) — простой вики-движок на PHP, использующий MySQL для хранения данных;
- [DokuWiki](https://www.dokuwiki.org/dokuwiki) — простой, но достаточно мощный вики-движок;
- [Gollum](https://github.com/gollum/gollum) — простой вики-движок, построенный на основе Git;
- [ikiwiki](http://ikiwiki.info/) — вики-компилятор;
- [MDwiki](http://dynalon.github.io/mdwiki/#!index.md) — вики, полностью написанная на HTML5/JavaScript;
- [MediaWiki](http://www.mediawiki.org/wiki/MediaWiki) — движок для вики-проектов, который был написан специально для Википедии;
- [MoinMoin](http://moinmo.in/) — мощный, простой в использовании и расширяемый вики-движок, написанный на Python;
- [Ōlelo Wiki](https://github.com/minad/olelo) — вики-движок, построенный на основе Git;
- [TiddlyWiki](http://tiddlywiki.com/) — вики-движок и вики-концепция, заключающаяся в том, что весь вики-сайт представляет собой одну HTML-страницу, интерактивность которой обеспечивается скриптами.

## Блоги

- [Code as Craft](http://codeascraft.com/) — блог компании Etsy;
- [DevOpsGuys](http://blog.devopsguys.com/) — блог devops’ов;
- [Rackspace Developers](http://developer.rackspace.com/blog/) — блог с множеством статей на тему DevOps;

## Книги

- [Learn Cisco Network Administration in a Month of Lunches](https://www.manning.com/books/learn-cisco-network-administration-in-a-month-of-lunches) — руководство для сисадминов, которые хотят научиться администрировать коммутаторы и маршрутизаторы Cisco;
- [The Linux Command Line](http://linuxcommand.org/tlcl.php) — книга о командной строке Linux;
- [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) — книга о том, как DevOps-методики могут решить проблемы в IT-организациях;
- [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) — в первом и втором изданиях описываются лучшие практики администрирования, вне зависимости от конкретных платформ или технологий;
- [UNIX and Linux System Administration Handbook](http://www.admin.com/) — подход к системному администрированию с практической точки зрения;
- [Securing DevOps](https://manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) — книги о безопасности для DevOps, которая рассматривает современные технологии, используемые для защиты веб-приложений и их инфраструктуры.

## Рассылки для сисадминов

- [Servers for Hackers](http://serversforhackers.com/) — рассылка для программистов, которым нужно администрировать сервер;
- [DevOpsLinks](http://devopslinks.com/) — сообщество DevOps, сисадминов и разработчиков с еженедельной рассылкой и чатом;

## Репозитории

- [Dotdeb](http://www.dotdeb.org/) — репозиторий с обновлёнными Debian-пакетами для LAMP;
- [ElRepo](http://elrepo.org/tiki/tiki-index.php) — репозиторий сообщества для Enterprise Linux (RHEL, Centos и т.д.);
- [EPEL](https://fedoraproject.org/wiki/EPEL) — репозиторий для RHEL и совместимых с ним (CentOS, Scientific Linux);
- [Remi](http://rpms.famillecollet.com/) — репозиторий с обновлёнными LAMP-пакетами для RHEL/Centos/Fedora.
- [Software Collections](https://www.softwarecollections.org/) — предоставляет обновлённые пакеты Ruby, Python, и т.д. для CentOS/Scientific Linux 6.x.

## Сайты

- [Ops School](http://www.opsschool.org/) — исчерпывающая программа, которая расскажет, как стать operations engineer;
- [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) — удивительно обширный ресурс провайдера облачных инфраструктур для изучения основ определённых приложений, инструментов и даже системного администрирования.

115К открытий118К показов
