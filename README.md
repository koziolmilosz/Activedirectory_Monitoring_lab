🖥️ Home Lab – Enterprise Windows Domain + Linux Monitoring
Opis projektu

To laboratorium symuluje środowisko IT małej firmy z kompletną infrastrukturą sieciową i monitoringiem.
Celem projektu było zdobycie praktycznych umiejętności administracji Windows Server, Active Directory oraz monitoringu serwerów przy użyciu Prometheus + Grafana.

🌐 Infrastruktura

-Domain Controller / Router (Windows Server, 2 GB RAM)

  Active Directory (AD DS)

  DNS, DHCP

  GPO: Desktop policies, logon scripts, mapped drives

  Dwie karty sieciowe: wewnętrzna LAN + zewnętrzna (symulacja routingu)

-Client VM (Windows 10/11, 3 GB RAM)

  Członek domeny

  Testuje Przydzielone dyski i GPO 

  Testuje użytkowników 


-Linux Server (Ubuntu Server, np. 2 GB RAM)

  Członek domeny (opcjonalnie)

  Monitoring z Prometheus + Grafana

  Śledzenie DC





🛠️ Administracja Active Directory

  Utworzone OU działów: HR, IT, Sales

  Utworzone grupy bezpieczeństwa: HR_SG, IT_SG, Sales_SG

  Przypisanie użytkowników do OU i grup

  Konfiguracja GPO:

  Logon scripts

  Mapped drives

  Desktop wallpaper (UNC path)

  Password policies

  Troubleshooting i testowanie GPO

  Symulacja dostępu do plików zgodnie z zasadami bezpieczeństwa



📊 Monitoring i Linux Server

  Zainstalowany Prometheus na Linux Server

  Zbieranie metryk z DC



Windows Client

Grafana:

Dashboardy z CPU, RAM, dyskiem i Użyciem sieci 
