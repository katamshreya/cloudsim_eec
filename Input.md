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
machine class:
{
        Number of machines: 16
        CPU type: X86
        Number of cores: 8
        Memory: 16384
        S-States: [120, 100, 100, 80, 40, 10, 0]
        P-States: [12, 8, 6, 4]
        C-States: [12, 3, 1, 0]
        MIPS: [1000, 800, 600, 400]
        GPUs: yes
}

machine class:
{
        Number of machines: 24
        CPU type: ARM
        Number of cores: 16
        Memory: 16384
        S-States: [120, 100, 100, 80, 40, 10, 0]
        P-States: [12, 8, 6, 4]
        C-States: [12, 3, 1, 0]
        MIPS: [1000, 800, 600, 400]
        GPUs: yes
}

machine class:
{
        Number of machines: 8
        CPU type: X86
        Number of cores: 4
        Memory: 8192
        S-States: [100, 80, 60, 40, 20, 0]
        P-States: [10, 8, 6, 4]
        C-States: [10, 5, 1, 0]
        MIPS: [500, 400, 300, 200]
        GPUs: no
}

machine class:
{
        Number of machines: 12
        CPU type: ARM
        Number of cores: 32
        Memory: 32768
        S-States: [150, 120, 100, 80, 50, 10, 0]
        P-States: [16, 12, 8, 4]
        C-States: [15, 10, 5, 0]
        MIPS: [2000, 1500, 1000, 500]
        GPUs: yes
}

machine class:
{
        Number of machines: 4
        CPU type: RISC-V
        Number of cores: 2
        Memory: 4096
        S-States: [80, 60, 40, 20, 0]
        P-States: [8, 6, 4, 2]
        C-States: [8, 4, 1, 0]
        MIPS: [300, 200, 150, 100]
        GPUs: no
}

machine class:
{
        Number of machines: 6
        CPU type: X86
        Number of cores: 64
        Memory: 65536
        S-States: [200, 150, 120, 80, 40, 10, 0]
        P-States: [32, 16, 8, 4]
        C-States: [25, 15, 5, 0]
        MIPS: [4000, 3000, 2000, 1000]
        GPUs: yes
}

machine class:
{
        Number of machines: 10
        CPU type: ARM
        Number of cores: 8
        Memory: 12288
        S-States: [120, 100, 80, 60, 40, 20, 0]
        P-States: [12, 8, 6, 4]
        C-States: [12, 6, 3, 0]
        MIPS: [1000, 800, 600, 400]
        GPUs: no
}

machine class:
{
        Number of machines: 2
        CPU type: POWER
        Number of cores: 128
        Memory: 131072
        S-States: [250, 200, 150, 100, 50, 10, 0]
        P-States: [64, 32, 16, 8]
        C-States: [50, 25, 10, 0]
        MIPS: [8000, 6000, 4000, 2000]
        GPUs: yes
}

task class:
{
        Start time: 1000
        End time : 100000
        Inter arrival: 100
        Expected runtime: 5000
        Memory: 4
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA0
        CPU type: X86
        Task type: WEB
        Seed: 520301
}

task class:
{
        Start time: 5000
        End time : 200000
        Inter arrival: 500
        Expected runtime: 15000
        Memory: 8
        VM type: WINDOWS
        GPU enabled: yes
        SLA type: SLA1
        CPU type: ARM
        Task type: HPC
        Seed: 520302
}

task class:
{
        Start time: 10000
        End time : 500000
        Inter arrival: 1000
        Expected runtime: 50000
        Memory: 16
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA2
        CPU type: X86
        Task type: STREAMING
        Seed: 520303
}

task class:
{
        Start time: 2000
        End time : 300000
        Inter arrival: 200
        Expected runtime: 10000
        Memory: 2
        VM type: WINDOWS
        GPU enabled: no
        SLA type: SLA3
        CPU type: RISC-V
        Task type: WEB
        Seed: 520304
}

task class:
{
        Start time: 8000
        End time : 400000
        Inter arrival: 300
        Expected runtime: 20000
        Memory: 4
        VM type: LINUX
        GPU enabled: yes
        SLA type: SLA0
        CPU type: POWER
        Task type: HPC
        Seed: 520305
}

task class:
{
        Start time: 15000
        End time : 450000
        Inter arrival: 250
        Expected runtime: 15000
        Memory: 8
        VM type: WINDOWS
        GPU enabled: yes
        SLA type: SLA1
        CPU type: ARM
        Task type: STREAMING
        Seed: 520306
}

task class:
{
        Start time: 30000
        End time : 500000
        Inter arrival: 500
        Expected runtime: 25000
        Memory: 16
        VM type: LINUX
        GPU enabled: no
        SLA type: SLA2
        CPU type: X86
        Task type: HPC
        Seed: 520307
}

task class:
{
        Start time: 12000
        End time : 600000
        Inter arrival: 100
        Expected runtime: 5000
        Memory: 2
        VM type: WINDOWS
        GPU enabled: no
        SLA type: SLA3
        CPU type: ARM
        Task type: WEB
        Seed: 520308
}

task class:
{
        Start time: 25000
        End time : 700000
        Inter arrival: 200
        Expected runtime: 10000
        Memory: 4
        VM type: LINUX
        GPU enabled: yes
        SLA type: SLA0
        CPU type: POWER
        Task type: STREAMING
        Seed: 520309
}

task class:
{
        Start time: 40000
        End time : 800000
        Inter arrival: 300
        Expected runtime: 15000
        Memory: 8
        VM type: WINDOWS
        GPU enabled: no
        SLA type: SLA1
        CPU type: X86
        Task type: HPC
        Seed: 520310
}

task class:
{
        Start time: 60000
        End time : 900000
        Inter arrival: 400
        Expected runtime: 20000
        Memory: 16
        VM type: LINUX
        GPU enabled: yes
        SLA type: SLA2
        CPU type: ARM
        Task type: WEB
        Seed: 520311
}

task class:
{
        Start time: 80000
        End time : 1000000
        Inter arrival: 500
        Expected runtime: 25000
        Memory: 32
        VM type: WINDOWS
        GPU enabled: yes
        SLA type: SLA3
        CPU type: POWER
        Task type: HPC
        Seed: 520312
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


