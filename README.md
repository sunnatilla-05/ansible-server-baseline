# ansible-server-baseline
Плейбук с тремя ролями: base (UFW, fail2ban, пакеты), ssh_hardening (запрет root и входа по паролю) и nginx (шаблон конфигурации и /healthz). Рассчитан на повторный запуск без побочных изменений и подходит для вашего Homelab на Ubuntu Server в VirtualBox. Он подтверждает пункт резюме про стандартизацию конфигурации серверов.
