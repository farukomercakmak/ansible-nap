# ansible-nap - Ansible ile Nextcloud + Apache + PostgreSQL Kurulumu

Notlar:

* vars/main.yml de veritabanı bilgileri bulunmaktadır.
* roles/phpsettings/files altında php.ini dosyası bulunmaktadır.
memory_limit, upload_max_filesize, post_max_size, max_execution_time, date.timezone değerleri bu dosyada belirlenmiştir.
* nextcloud_playbook.yml dosyasındaki hosts bilgisi kendi sunucu bilgilerinize göre düzenlenmelidir.

# Çalıştırma

  ansible-playbook nextcloud_playbook.yml
