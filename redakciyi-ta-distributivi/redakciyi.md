# Редакції

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

## Fedora Workstation

Fedora Workstation — це редакція Fedora що побудована на базі робочого середовища GNOME.

Оболонка GNOME має естетичний вигляд і за дизайном дещо нагадує macOS, тому до її філософії керування системою потрібно трохи звикнути. Оскільки розробники GNOME приділяють особливу увагу надійності та дизайну, ця редакція вважається дуже стабільною та рекомендується початківцям.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Офіційний сайт  <a href="https://www.gnome.org/">Gnome</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/workstation/download/" %}

## Fedora KDE Plasma Desktop

Fedora KDE Plasma Desktop — це редакція Fedora що побудована на базі середовищя KDE plasma.&#x20;

Оболонка KDE Plasma — це оболонка, що дуже схожа на Windows, але вона має дуже велику кастомізацію, а також дуже багато додаткових програм, які інтегруються з оболонкою KDE. Розробники KDE приділяють велику увагу функціоналу та новим технологіям. Вона є найпопулярнішою оболонкою (на мою думку) в Linux та використовується на таких пристроях, як [Steam Deck](https://store.steampowered.com/steamdeck), в їхній фірмовій [SteamOS](https://store.steampowered.com/steamos/).

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Офіційний сайт <a href="https://kde.org/products/">KDE</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/kde/" %}

## Fedora Server

Fedora Server - це редакція яка спецівлізована для серверів.

Ця редакція відрізняється тим, що її можна налаштувати під потреби вашого сервера. Вона використовує модифікований інсталятор системи Anaconda, де ви можете вибрати будь-яку оболонку, а також потрібні вам інструменти для роботи з сервером.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Офіційний сайт <a href="https://fedoraproject.org/server/">Fedora Server</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/server/download/" %}

## Fedora Cloud

Fedora cloud - це редакція Fedora що використовується для хмарного хостингу та хмарних інфраструктур.&#x20;

Вона постачається у вигляді вичищеного та мінімалістичного базового образу (Base Image), оптимізованого для швидкого розгортання у хмарах ([AWS](https://aws.amazon.com/?nc2=h_home\&trk=ea4f1bda-c329-47b3-a6d0-278045ca3aea\&sc_channel=ps), [OpenStack](https://www.openstack.org/), [Google Cloud](https://cloud.go/), [DigitalOcean](https://www.digitalocean.com/)) та віртуалізації ([KVM](https://www.redhat.com/en/topics/virtualization/what-is-KVM), [QEMU](https://www.qemu.org/)). Завдяки відсутності зайвих пакетів система споживає мінімум ресурсів і завантажується за лічені секунди.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Офіційний сайт <a href="https://fedoraproject.org/cloud/">Fedora Cloud</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/cloud/download/" %}

Джерело: [Reddit](https://www.reddit.com/r/Fedora/comments/347q57/what_is_the_difference_between_fedora_cloud_and/?tl=uk)

## Fedora CoreOS

Fedora CoreOS — мінімалістична незмінна ОС, що об'єднала технології Fedora Atomic Host та CoreOS Container Linux.

Вона містить лише ядро Linux, systemd, SSH і середовище виконання контейнерів. Система орієнтована на автоматичний запуск контейнерів і конфігурується під час першого завантаження через мережу або хмару.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Офіційний сайт<a href="https://fedoraproject.org/coreos/"> Fedora CoreOS</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/coreos/download/" %}

Джерело: [teamquest.pl](https://teamquest.pl/blog/1504_fedora-coreos)

## Fedora IoT

Fedora IoT — це спеціальна Linux-система для пристроїв Інтернету речей (IoT). Вона є повністю незмінною (_immutable_) та підтримує атомарні оновлення з можливістю відкату (_rollback_), що гарантує стабільну роботу віддаленого обладнання навіть у разі збоїв.

ОС працює через `rpm-ostree`, що дозволяє за потреби накладати додаткові RPM-пакети. Вона орієнтована на контейнери та має вбудований Podman для ізольованого запуску додатків на кшталт Home Assistant чи систем аналітики.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Офіційний сайт <a href="https://fedoraproject.org/iot/">Fedora IOT</a></p></figcaption></figure>

{% embed url="https://fedoraproject.org/iot/download/" %}

Джерело: [Fedora Docs](https://docs.fedoraproject.org/en-US/iot/)
