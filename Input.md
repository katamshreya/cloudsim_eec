machine class:
{
        Number of machines: 12
        CPU type: X86
        Number of cores: 12
        Memory: 32768
        S-States: [200, 160, 150, 120, 60, 15, 0]
        P-States: [16, 12, 8, 4]
        C-States: [16, 6, 2, 0]
        MIPS: [2000, 1600, 1200, 800]
        GPUs: yes
}
machine class:
{
        Number of machines: 12
        CPU type: RISCV
        Number of cores: 8
        Memory: 16384
        S-States: [90, 70, 60, 40, 20, 6, 0]
        P-States: [10, 8, 6, 4]
        C-States: [10, 3, 1, 0]
        MIPS: [900, 700, 500, 300]
        GPUs: no
}
task class:
{
        Start time: 0
        End time : 600000000
        Inter arrival: 1500000
        Expected runtime: 800000
        Memory: 16
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA1
        CPU type: RISCV
        Task type: WEB
        Seed: 222
}
task class:
{
        Start time: 120000000
        End time : 240000000
        Inter arrival: 20000
        Expected runtime: 400000
        Memory: 32
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA0
        CPU type: X86
        Task type: STREAM
        Seed: 223
}
task class:
{
        Start time: 200000000
        End time : 220000000
        Inter arrival: 5000
        Expected runtime: 200000
        Memory: 8
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA0
        CPU type: X86
        Task type: WEB
        Seed: 224
}


