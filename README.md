# The Linux Kernel review for ARMv7 3.13.x (exynos 5420)
All of this repository by hephaex@gmail.com.

Community name: kernel study 
Target Soc    : Samsung Exynos 5420 (ARMv7 A7&A15 bigLITTLE )
Kernel version: Linux kernel 3.13.x
 - 1st: 3.10.x, A bootstrab before start_kernel(): 3.10.x
 - 2nd: start_kernel()->mm_init: 3.13.x 

# The history of Linux kernel study
* 163th (2016/11/26) week [163차](https://github.com/hephaex/kernel_review/blob/master/a10c_163.md)
 - rest_init()
* 162th (2016/11/12) week [162차](https://github.com/hephaex/kernel_review/blob/master/a10c_162.md)
 - rest_init() 
* 161th (2016/11/05) week [161차](https://github.com/hephaex/kernel_review/blob/master/a10c_161.md)
 - rest_init()
* 160th (2016/07/20) week [160차](https://github.com/hephaex/kernel_review/blob/master/a10c_160.md)
 - rest_init()
* 159th (2016/07/20) week [159차](https://github.com/hephaex/kernel_review/blob/master/a10c_159.md)
 - rest_init()
* 158th (2016/07/13) week [158차](https://github.com/hephaex/kernel_review/blob/master/a10c_158.md)
 - rest_init()
* 157th (2016/08/06) week [157차](https://github.com/hephaex/kernel_review/blob/master/a10c_157.md)
 - rest_init()
* 156th (2016/07/30) week [156차](https://github.com/hephaex/kernel_review/blob/master/a10c_156.md)
 - cgroup_init()
 - rest_init()
* 155th (2016/07/30) week [153차](https://github.com/hephaex/kernel_review/blob/master/a10c_155.md)
 - cgroup_init()
* 154th (2016/07/30) week [153차](https://github.com/hephaex/kernel_review/blob/master/a10c_154.md)
 - cgroup_init()
* 153th (2016/07/30) week [153차](https://github.com/hephaex/kernel_review/blob/master/a10c_153.md)
 - cgroup_init()
* 152th (2016/07/23) week [152차](https://github.com/hephaex/kernel_review/blob/master/a10c_152.md)
 - cgroup_init()
* 151th (2016/07/16) week [151차](https://github.com/hephaex/kernel_review/blob/master/a10c_151.md)
 - proc_root_init()
 - cgroup_init()
* 150th (2016/07/09) week [150차](https://github.com/hephaex/kernel_review/blob/master/a10c_150.md)
 - proc_root_init()
* 149th (2016/07/02) week [149차](https://github.com/hephaex/kernel_review/blob/master/a10c_149.md)
 - vfs_caches_init()
* 148th (2016/06/25) week [148차](https://github.com/hephaex/kernel_review/blob/master/a10c_148.md)
 - vfs_caches_init()
* 147th (2016/06/10) week [147차](https://github.com/hephaex/kernel_review/blob/master/a10c_147.md)
 - vfs_caches_init()
* 146th (2016/06/03) week [146차](https://github.com/hephaex/kernel_review/blob/master/a10c_146.md)
 - vfs_caches_init()
* 145th (2016/05/27) week [145차](https://github.com/hephaex/kernel_review/blob/master/a10c_145.md)
 - vfs_caches_init()
* 144th (2016/05/20) week [144차](https://github.com/hephaex/kernel_review/blob/master/a10c_144.md)
 - vfs_caches_init()
* 143th (2016/05/13) week [143차](https://github.com/hephaex/kernel_review/blob/master/a10c_143.md)
 - vfs_caches_init()
* 142th (2016/04/30) week [142차](https://github.com/hephaex/kernel_review/blob/master/a10c_142.md)
 - vfs_caches_init()
   - mnt_init()
   - init_mount_tree()
* 141th (2016/04/23) week [141차](https://github.com/hephaex/kernel_review/blob/master/a10c_141.md)
 - vfs_caches_init()
   - mnt_init()
   - init_mount_tree()
* 140th (2016/04/16) week [140차](https://github.com/hephaex/kernel_review/blob/master/a10c_140.md)
 - vfs_caches_init()
   - mnt_init()
   - init_mount_tree()
* 139th (2016/04/09) week [139차](https://github.com/hephaex/kernel_review/blob/master/a10c_139.md)
 - vfs_caches_init()
   - mnt_init()
   - init_mount_tree()
* 138th (2016/03/26) week [138차](https://github.com/hephaex/kernel_review/blob/master/a10c_138.md)
 - vfs_caches_init()
  - mnt_init()
  - shmem_init()
* 137th (2016/03/26) week [137차](https://github.com/hephaex/kernel_review/blob/master/a10c_137.md)
 - vfs_caches_init()
  - mnt_init()
  - shmem_init()
* 136th (2016/03/19) week [136차](https://github.com/hephaex/kernel_review/blob/master/a10c_136.md)
 - vfs_caches_init()
  - mnt_init()
  - shmem_init()
* 135th (2016/03/05) week [135차](https://github.com/hephaex/kernel_review/blob/master/a10c_135.md)
 - vfs_caches_init()
  - mnt_init()
  - shmem_init()
* 134th (2016/02/27) week [134차](https://github.com/hephaex/kernel_review/blob/master/a10c_134.md)
 - vfs_caches_init()
  - mnt_init()
  - shmem_init()
* 133th (2016/02/20) week [133차](https://github.com/hephaex/kernel_review/blob/master/a10c_133.md)
 - vfs_caches_init()
  - mnt_init()
* 132th (2016/02/13) week [132차](https://github.com/hephaex/kernel_review/blob/master/a10c_132.md)
 - vfs_caches_init()
  - mnt_init()
* 131th (2016/01/23) week [131차](https://github.com/hephaex/kernel_review/blob/master/a10c_131.md)
 - vfs_caches_init()
  - mnt_init()
* 130th (2016/01/16) week [130차](https://github.com/hephaex/kernel_review/blob/master/a10c_130.md)
 - vfs_caches_init()
  - mnt_init()
* 129th (2016/01/09) week [129차](https://github.com/hephaex/kernel_review/blob/master/a10c_129.md)
 - vfs_caches_init()
  - mnt_init()
* 128th (2015/12/19) week [128차](https://github.com/hephaex/kernel_review/blob/master/a10c_128.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 127th (2015/12/12) week [127차](https://github.com/hephaex/kernel_review/blob/master/a10c_127.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 126th (2015/12/05) week [126차](https://github.com/hephaex/kernel_review/blob/master/a10c_126.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 125th (2015/11/27) week [125차](https://github.com/hephaex/kernel_review/blob/master/a10c_125.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 124th (2015/11/21) week [124차](https://github.com/hephaex/kernel_review/blob/master/a10c_124.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 123th (2015/11/14) week [123차](https://github.com/hephaex/kernel_review/blob/master/a10c_123.md)
 - vfs_caches_init()
  - mnt_init()
    - sysfs_init()
* 122th (2015/11/07) week [122차](https://github.com/hephaex/kernel_review/blob/master/a10c_122.md)
 - vfs_caches_init()
* 121th (2015/10/31) week [121차](https://github.com/hephaex/kernel_review/blob/master/a10c_121.md)
 - vfs_caches_init()
* 120th (2015/10/24) week [120차](https://github.com/hephaex/kernel_review/blob/master/a10c_120.md)
 - vfs_caches_init()
* 119th (2015/10/10) week [119차](https://github.com/hephaex/kernel_review/blob/master/a10c_119.md)
* 118th (2015/10/03) week [118차](https://github.com/hephaex/kernel_review/blob/master/a10c_118.md)
* 117th (2015/09/19) week [117차](https://github.com/hephaex/kernel_review/blob/master/a10c_117.md)
 - pidmap_init()
* 116th (2015/09/13) week [116차](https://github.com/hephaex/kernel_review/blob/master/a10c_116.md)
* 115th (2015/08/22) week [115차](https://github.com/hephaex/kernel_review/blob/master/a10c_115.md)
 - cgroup_early_init() 분석
* 114th (2015/08/15) week [114차](https://github.com/hephaex/kernel_review/blob/master/a10c_114.md)
 - cgorup 초기 초기화 분석
 - cgroup_early_init()
* 113th (2015/08/08) week [113차](https://github.com/hephaex/kernel_review/blob/master/a10c_113.md)
 - cgorup 초기 초기화 분석
 - cgroup_early_init()
* 112th (2015/08/01) week [112차](https://github.com/hephaex/kernel_review/blob/master/a10c_112.md)
 - cgroup 에 대한 이야기
 - LXC와 Docker 기술
 - SS의 G6의 kernel config 를 참조하여 cgroup config를 설정.
 - config 추가: Reference/exynos7420-zerolte_kor_skc_defconfig
 - pageconsole_init()
* 111th (2015/07/25) week [111차](https://github.com/hephaex/kernel_review/blob/master/a10c_111.md)
 - console_init()
  - con_init()* 110th (2015/07/18) week [110차](https://github.com/hephaex/kernel_review/blob/master/a10c_110.md)
 - console_init()
  - con_init()
* 109th (2015/07/11) week [109차](https://github.com/hephaex/kernel_review/blob/master/a10c_109.md)
 - console_init()
  - con_init()
* 108th (2015/07/04) week [108차](https://github.com/hephaex/kernel_review/blob/master/a10c_108.md)
 - parse_args() 복습
 - console_init()->con_init()
 - console_init()->s3c24xx_serial_console_init()
* 107th (2015/06/27) week [107차](https://github.com/hephaex/kernel_review/blob/master/a10c_107.md)
 - console_init()
* 106th (2015/06/20) week [106차](https://github.com/hephaex/kernel_review/blob/master/a10c_106.md)
 - sched_clock_postinit();
 - perf_event_init();
 - profile_init();
 - call_function_init();
 - irqs_disabled()
 - local_irq_enable();
 - kmem_cache_init_late();
* 105th (2015/06/13) week [105차](https://github.com/hephaex/kernel_review/blob/master/a10c_105.md)
 - sched_clock_postinit();
* 104th (2015/06/06) week [104차](https://github.com/hephaex/kernel_review/blob/master/a10c_104.md)
 - sched_clock_postinit();
* 103th (2015/05/30) week [103차](https://github.com/hephaex/kernel_review/blob/master/a10c_103.md)
 - sched_clock_postinit();
* 102th (2015/05/23) week [102차](https://github.com/hephaex/kernel_review/blob/master/a10c_102.md)
 - time_init()
   - timer 를 사용하기 위한 clk source, clk_table 메모리 할당 및 초기화,
   - timer event를 위한 timer irq (MCT) 초기화 수행
* 101th (2015/05/16) week [101차](https://github.com/hephaex/kernel_review/blob/master/a10c_101.md)
* 100th (2015/04/25) week [100차](https://github.com/hephaex/kernel_review/blob/master/a10c_100.md)
 - NIPA 5층 대강당, 12차 Iamroot OT.
 - 개발에 대한 자유토론. (IoT, 3D/4D Printing, 라즈베리파이2, 오드로이드...)
* 99th (2015/04/19) week [99차](https://github.com/hephaex/kernel_review/blob/master/a10c_99.md)
* 98th (2015/04/11) week [98차](https://github.com/hephaex/kernel_review/blob/master/a10c_98.md)
* 97th (2015/04/04) week [97차](https://github.com/hephaex/kernel_review/blob/master/a10c_97.md)
* 96th (2015/03/28) week [96차](https://github.com/hephaex/kernel_review/blob/master/a10c_96.md)
 - start_kernel()->time_init()->clocksource_of_init()->mct_init_spi()->mct_init_dt()->irq_of_parse_and_map()
* 95th (2015/03/21) week [95차](https://github.com/hephaex/kernel_review/blob/master/a10c_95.md)
 - start_kernel()->time_init()->clocksource_of_init()->mct_init_spi()->mct_init_dt()->irq_of_parse_and_map()->of_irq_parse_one()->of_irq_parse_raw()
* 94th (2015/03/14) week [94차](https://github.com/hephaex/kernel_review/blob/master/a10c_94.md)
 - start_kernel()->time_init()->clocksource_of_init()->mct_init_spi()->mct_init_dt()->irq_of_parse_and_map()
* 93th (2015/03/07) week [93차](https://github.com/hephaex/kernel_review/blob/master/a10c_93.md)
 - start_kernel()->time_init()->of_clk_init()
 - sta rt_kernel()->time_init()->clocksource_of_init()->mct_init_spi()->mct_init_dt()->irq_of_parse_and_map()
* 92th (2015/02/28) week [92차](https://github.com/hephaex/kernel_review/blob/master/a10c_92.md)
 - start_kernel()->time_init()->of_clk_init()
* 91th (2015/02/21) week [91차](https://github.com/hephaex/kernel_review/blob/master/a10c_91.md)
 - start_kernel()->time_init()->of_clk_init()
* 90th (2015/02/07) week [90차](https://github.com/hephaex/kernel_review/blob/master/a10c_90.md)
 - start_kernel()->time_init()->of_clk_init()
* 89th (2015/01/31) week [89차](https://github.com/hephaex/kernel_review/blob/master/a10c_89.md)
 - start_kernel()->time_init()->of_clk_init()
* 88th (2015/01/24) week [88차](https://github.com/hephaex/kernel_review/blob/master/a10c_88.md)
 - start_kernel()->time_init()->of_clk_init()
* 87th (2015/01/17) week [87차](https://github.com/hephaex/kernel_review/blob/master/a10c_87.md)
 - start_kernel()->time_init()->of_clk_init()
* 86th (2015/01/10) week [86차](https://github.com/hephaex/kernel_review/blob/master/a10c_86.md)
 - start_kernel()->time_init()->of_clk_init()
* 85th (2015/01/03) week [85차](https://github.com/hephaex/kernel_review/blob/master/a10c_85.md)
 - start_kernel()->time_init()->of_clk_init()
* 84th (2014/12/27) week [84차](https://github.com/hephaex/kernel_review/blob/master/a10c_84.md)
 - start_kernel()->time_init()->of_clk_init()
* 83th (2014/12/20) week [83차](https://github.com/hephaex/kernel_review/blob/master/a10c_83.md)
* 82th (2014/12/13) week [82차](https://github.com/hephaex/kernel_review/blob/master/a10c_82.md)
* 81th (2014/12/06) week [81차](https://github.com/hephaex/kernel_review/blob/master/a10c_81.md)
 - init_IRQ()->...->kfree()
* 80th (2014/11/29) week [80차](https://github.com/hephaex/kernel_review/blob/master/a10c_80.md)
 - init_IRQ()->...->gic_of_init()->gic_of_bases()
 - irqchip_init()
* 79th (2014/11/22) week [79차](https://github.com/hephaex/kernel_review/blob/master/a10c_79.md)
 - init_IRQ()->...->gic_of_init()->gic_of_bases()
* 78th (2014/11/15) week [78차](https://github.com/hephaex/kernel_review/blob/master/a10c_78.md)
 - init_IRQ()->...->gic_of_init()
 - Radix-tree
* 77th (2014/11/08) week [77차](https://github.com/hephaex/kernel_review/blob/master/a10c_77.md)
 - init_IRQ()->...->gic_of_init()
* 76th (2014/11/01) week [76차](https://github.com/hephaex/kernel_review/blob/master/a10c_76.md)
 - init_IRQ()
* 75th (2014/10/25) week [75차](https://github.com/hephaex/kernel_review/blob/master/a10c_75.md)
 - init_IRQ()
 - RBTree 알고리즘 분석
* 74th (2014/10/18) week [74차](https://github.com/hephaex/kernel_review/blob/master/a10c_74.md)
 - init_IRQ()
* 73th (2014/10/11) week [73차](https://github.com/hephaex/kernel_review/blob/master/a10c_73.md)
 - init_IRQ()
* 72th (2014/10/04) week [72차](https://github.com/hephaex/kernel_review/blob/master/a10c_72.md)
* 71th (2014/09/27) week [71차](https://github.com/hephaex/kernel_review/blob/master/a10c_71.md)
* 70th (2014/09/20) week [70차](https://github.com/hephaex/kernel_review/blob/master/a10c_70.md)
* 69th (2014/09/13) week [69차](https://github.com/hephaex/kernel_review/blob/master/a10c_69.md)
 - sched_init()를 계속 분석
 - sched_init()::for_each_possible_cpu(i) { ... }
 - sched_init()->set_load_weight()
 - sched_init()->plist_head_init()
 - sched_init()->init_idle()
 - sched_init()->zalloc_cpumask_var()
* 68th (2014/08/30) week [68차](https://github.com/hephaex/kernel_review/blob/master/a10c_68.md)
 - sched_init()를 계속 분석
 - sched_init()->init_defrootdomain()
  - // def_root_domain의 맴버 값을 초기화 수행
 - sched_init()->init_rt_bandwidth(&def_rt_bandwidth, global_rt_period(), global_rt_runtime());
 - sched_init()::for_each_possible_cpu(i) { ... } 
* 67th (2014/08/23) week [67차](https://github.com/hephaex/kernel_review/blob/master/a10c_67.md)
 - mm_init() 복습
 - slub()　복습
* 66th (2014/08/16) week [66차](https://github.com/hephaex/kernel_review/blob/master/a10c_66.md)
 - mm_init() 복습;
 - buddy 까지 복습 (mem_init())
* 65th (2014/08/09) week [65차](https://github.com/hephaex/kernel_review/blob/master/a10c_65.md)
 - start_kernel()-> mm_init()-> vmalloc_init();
 - vmlist에 등록된 vm struct 들을 slab으로 이관하고 RB Tree로 구성
* 64th (2014/07/26) week [64차](https://github.com/hephaex/kernel_review/blob/master/a10c_64.md)
 - start_kernel()-> mm_init()-> kmem_cache_init()
 - start_kernel()-> mm_init()-> percpu_init_late()
 - start_kernel()-> mm_init()-> pgtable_cache_init()
* 63th (2014/07/19) week [63차](https://github.com/hephaex/kernel_review/blob/master/a10c_63.md)
 - mm_init()->kmem_cache_init()->bootstrab(&boot_kmem_cache_node) 
* 62th (2014/07/12) week [62차](https://github.com/hephaex/kernel_review/blob/master/a10c_62.md)
 - mm_init()->kmem_cache_init()->bootstrab(&boot_kmem_cache) 
* 61th (2014/07/05) week [61차](https://github.com/hephaex/kernel_review/blob/master/a10c_61.md)
* 60th (2014/06/28) week [60차](https://github.com/hephaex/kernel_review/blob/master/a10c_60.md)
* 59th (2014/06/21) week [59차](https://github.com/hephaex/kernel_review/blob/master/a10c_59.md)
* 58th (2014/06/14) week [58차](https://github.com/hephaex/kernel_review/blob/master/a10c_58.md)
* 57th (2014/06/07) week [57차](https://github.com/hephaex/kernel_review/blob/master/a10c_57.md)
 - start_kernel()->mm_init()->kmem_cache_init()->create_boot_cache()
 - slab_state는 slab이 어느정도 활성화 되었는지를 나타낸다.
 - 지금까지 // slab_state: DOWN 에서 분석을 했고,
 - 이제는 slab_state = PARTIAL; 로 바뀌어 분석을 한다. 
 - 여기서  // slab_state의 의미는  slab을 초기화한 단계를 의미한다.
 - slab_stat = PARTIAL은  kmem_cache_node만 사용이 가능을 의미한다.
 - 계속해서 slab_stat = PARTIAL로 해서 create_boot_cache를 다시 실행한다. 
* 56th (2014/05/31) week [56차](https://github.com/hephaex/kernel_review/blob/master/a10c_56.md)
 - start_kernel()->mm_init()->kmem_cache_init()->create_boot_cache()
 - init_kmem_cache_nodes는 slab으로 사용할 page를 할당받아 설정값(slab_cache, flags, freelist, inuse, frozen)을 바꿔준다.
 - 이후 할당받은 slab object를 kmem_cache_node로 사용하며,
 - kmem_cache_node의 맴버 속성을 초기화합니다. 
 - 초기화되는 맴버속성은 (nr_partial, list_lock, slabs, full)가 있습니다.
* 55th (2014/05/24) week [55차](https://github.com/hephaex/kernel_review/blob/master/a10c_55.md)
 - start_kernel()->mm_init()->kmem_cache_init()->create_boot_cache()
 - new_slab()
* 54th (2014/05/17) week [54차](https://github.com/hephaex/kernel_review/blob/master/a10c_54.md) 
 - buddy할당자에 이어서 kmem 할당자 (Slub)을 분석중입니다. 
 - mem_init()->kmem_cache_init()->create_boot_cache()->__kmem_cache_create()
  ->kmem_cache_open()->init_kmem_cache_nodes->early_kmem_cache_node_alloc()
  ->new_slab()->allocate_slab()->alloc_slab_page()->alloc_pages_exact_node()
  ->__alloc_pages()->__alloc_pages_nodemask();
 - 커널 버전을 3.13.11로 바꿨습니다.
* 53th (2014/05/10) week [53차](https://github.com/hephaex/kernel_review/blob/master/a10c_53.md)  
* 52th (2014/04/26) week [52차](https://github.com/hephaex/kernel_review/blob/master/a10c_52.md)
* 51th (2014/04/19) week [51차](https://github.com/hephaex/kernel_review/blob/master/a10c_51.md)
* 50th (2014/04/12) week [50차](https://github.com/hephaex/kernel_review/blob/master/a10c_50.md)

...

* 23th (2013/09/28) week [23차](https://github.com/hephaex/kernel_review/blob/master/a10c_23.md)
* 22th (2013/09/21) week [22차](https://github.com/hephaex/kernel_review/blob/master/a10c_22.md)
 - boot/compressed/head.S
 - kernel/head.S
* 21th (2013/09/14) week [21차](https://github.com/hephaex/kernel_review/blob/master/a10c_21.md)
 - page_address_init()
 - pr_notice()
 - setup_arch()->setup_processor()
...

* 11th (2012-07-06) week [11차](https://github.com/hephaex/kernel_review/blob/master/a10c_11.md) 18+2명
 - arch/arm/boot/compressed/head.S 분석
 - _setup_mmu 종료
* 10th (2012-06-29) week [10차](https://github.com/hephaex/kernel_review/blob/master/a10c_10.md) 22명
 - arch/arm/boot/compressed/head.S 분석
 - _setup_mmu 진입직전
* 09th (2012-06-22) week [09차](https://github.com/hephaex/kernel_review/blob/master/a10c_09.md) 25명
 - Arm System Developer's Guide (Ch.14 ~ 끝)
 - arch/arm/boot/compressed/head.S 분석
 - call_cache_fn 진입직전
* 08th (2012-06-15) week [08차] 21명
 - Arm System Developer's Guide (Ch.09 ~ Ch.14.4 페이지 테이블)
* 07th (2012-06-08) week [07차] 20명
 - Arm System Developer's Guide (시작 ~ Ch.09 인터럽트 처리방법)
* 06th (2012-06-01) week [06차]
 - ARM v7 아키텍쳐 세미나
* 05th (2012-05-25) week [05차]
 - ARM v7 아키텍쳐 세미나
* 04th (2012-05-18) week [04차] 28명+1
 - Arm System Developer's Guide (pt자료)
* 03th (2012-05-11) week [03차] 22명
 - 리눅스 커널 내부구조 (p.150 ~ 끝)
* 02th (2012-05-04) week [02차] 27명
 - 리눅스 커널 내부구조 (p. 88~ p.150)
* 01th (2012-04-28) week [01차] 34명
 - 리눅스 커널 내부구조 (처음  ~ p. 88)
