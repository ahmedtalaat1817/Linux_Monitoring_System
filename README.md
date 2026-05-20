# Linux Monitoring System -
this is the tree structure of the project files and directories:

```linux-monitoring-system/
│
├── README.md
├── monitor.sh                   
├── config.conf                   
├── install.sh                  
│
├── scripts/
│   ├── resources/                
│   │   ├── cpu.sh
│   │   ├── memory.sh
│   │   ├── disk.sh
│   │   ├── network.sh
│   │   └── load.sh
│   │
│   ├── security/                 
│   │   ├── services.sh
│   │   ├── ssh_attempts.sh
│   │   ├── open_ports.sh
│   │   ├── users.sh
│   │   ├── file_integrity.sh
│   │   └── zombies.sh
│   │
│   ├── ui/                    
│   │   ├── colors.sh
│   │   ├── progress_bar.sh
│   │   ├── dashboard.sh
│   │   └── menu.sh
│   │
│   └── logging/                 
│       ├── log_writer.sh
│       ├── log_rotate.sh
│       ├── alerts.sh
│       └── daily_report.sh
│
├── logs/                         
│   └── .gitkeep
│
├── baseline/                     
│   └── .gitkeep
│
└── docs/
    ├── output_format.md          
    └── final_report.pdf
```
