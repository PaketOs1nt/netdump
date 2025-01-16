# netdump
local network scanner

 - есть сбор дампа открытых DNS записей
 - есть сбор дампа MAC

порты сканируются и сохраняются не только в отделььных папках (network_dump_*.*.*.*/192.168.*.*/ports.txt) а так же в более удобнов формате - network_dump_*.*.*.*/OPEN_PORTS/port.txt (список айпи адресов)

так же собираеться статистика устройств в сети в файле device_statistics.txt и в таком формате:
ios: 8
windows: 4
linux?: 2
