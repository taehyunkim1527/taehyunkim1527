---
layout: default
---

<section id="about">
    <h2 class="section-title">About Me</h2>
    <p>
        I am a <strong>Systems Software Engineer</strong> specializing in <strong>AI Infrastructure, DPU(SmartNIC), and Storage Systems</strong>. I bridge the gap between rapidly evolving hardware capabilities (GPUs, DPUs, NVMe) and software infrastructure for AI and Data-Intensive applications.
    </p>
    <p>
        Currently, I am a <strong>Software Engineer at MangoBoost</strong>, where I lead cross-functional projects to productize research-grade technologies. My work focuses on offloading storage/network I/O to DPUs and accelerating AI workloads through HW/SW co-design.
    </p>
    <p>
        I received my <strong>Ph.D. in Electrical Engineering from KAIST</strong>, where I researched Distributed Deep Learning, multi-tenant GPU cluster, Graph Neural Networks and High-Performance Networking.
    </p>
</section>

<section id="experience">
    <h2 class="section-title">Experience</h2>

    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">MangoBoost</span>
            <span class="timeline-meta">Feb 2024 - Present</span>
        </div>
        <div class="timeline-subtitle">Systems Software Engineer / Project manager (Storage & AI)</div>
        <p>Leading the development of DPU for storage offloading solutions and AI acceleration.</p>
        <ul class="skill-list">
            <li><strong>NVMe-oF & AI Acceleration:</strong> Productized NVMe-oF (TCP) initiator offload and Direct Data Path (NVIDIA GDS-like) for AI engines (vLLM/LMCache, DeepSpeed).</li>
            <li><strong>Storage Appliance:</strong> Designed and developed a DPU-accelerated high-performance & cost-effective storage appliance.</li>
            <li><strong>Host-DPU In-Band Management:</strong> Architected and built a virtual ethernet/console solution over PCIe, eliminating physical management cables.</li>
        </ul>
    </div>

    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">Microsoft Research</span>
            <span class="timeline-meta">Sep 2020 – Aug 2021</span>
        </div>
        <div class="timeline-subtitle">Research Intern</div>
        <p>Conducted research on distributed systems and AI infrastructure optimization.</p>
    </div>

    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">KAIST (NDSL Lab)</span>
            <span class="timeline-meta">Feb 2017 – Feb 2023</span>
        </div>
        <div class="timeline-subtitle">Graduate Research Assistant</div>
        <p>Researched high-performance networked systems and deep learning under Prof. KyoungSoo Park.</p>
    </div>
</section>

<section id="education">
    <h2 class="section-title">Education</h2>
    
    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">Korea Advanced Institute of Science and Technology (KAIST)</span>
            <span class="timeline-meta">Feb 2019 – Feb 2024</span>
        </div>
        <div class="timeline-subtitle">Ph.D. in Electrical Engineering</div>
        <p>Thesis: Optimizing Networked Systems for Distributed Deep Learning</p>
    </div>

    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">Korea Advanced Institute of Science and Technology (KAIST)</span>
            <span class="timeline-meta">Feb 2017 – Feb 2019</span>
        </div>
        <div class="timeline-subtitle">M.S. in Electrical Engineering</div>
    </div>

    <div class="timeline-item">
        <div class="timeline-header">
            <span class="timeline-title">Yonsei University</span>
            <span class="timeline-meta">Feb 2011 – Feb 2017</span>
        </div>
        <div class="timeline-subtitle">B.S. in Electrical Engineering</div>
    </div>
</section>

<section id="skills">
    <h2 class="section-title">Technical Skills</h2>
    <div class="skills-grid">
        <div class="skill-category">
            <h4>AI & ML Systems</h4>
            <ul class="skill-list">
                <li>vLLM, DeepSpeed, PyTorch, TensorFlow</li>
                <li>Distributed Training (Horovod, NCCL)</li>
                <li>GPU Direct Storage, KV Cache Opt.</li>
                <li>Graph Neural Networks</li>
            </ul>
        </div>
        <div class="skill-category">
            <h4>DPU & Storage</h4>
            <ul class="skill-list">
                <li>BlueField, ARM SoC + FPGA</li>
                <li>NVMe-oF (TCP & RDMA), SPDK, DPDK</li>
                <li>SW Defined Storage (Ceph, DAOS)</li>
            </ul>
        </div>
        <div class="skill-category">
            <h4>Systems & Kernel</h4>
            <ul class="skill-list">
                <li>Linux Kernel Module (LKM)</li>
                <li>Virtio, PCIe Subsystem</li>
                <li>TCP/IP, RDMA (RoCEv2)</li>
            </ul>
        </div>
        <div class="skill-category">
            <h4>Languages & Tools</h4>
            <ul class="skill-list">
                <li>C/C++, Python, CUDA</li>
                <li>Docker, Kubernetes, Git, GDB</li>
            </ul>
        </div>
    </div>
</section>

<section id="publications">
    <h2 class="section-title">Publications</h2>
    
    <div class="pub-item">
        <span class="pub-title">Rearchitecting the TCP Stack for I/O-Offloaded Content Delivery</span>
        <div class="pub-authors"><strong>Taehyun Kim</strong>, Deondre Martin Ng, Junzhi Gong, Youngjin Kwon, Minlan Yu, KyoungSoo Park</div>
        <div class="pub-venue">USENIX NSDI 2023</div>
        <div class="pub-links">
            <a href="https://www.usenix.org/conference/nsdi23/presentation/kim-taehyun" target="_blank">Paper</a>
        </div>
    </div>

    <div class="pub-item">
        <span class="pub-title">Accelerating GNN training with locality-aware partial execution</span>
        <div class="pub-authors"><strong>Taehyun Kim</strong>, Changho Hwang, KyoungSoo Park, et al.</div>
        <div class="pub-venue">ACM APSys 2021 <span style="color:#d35400; font-weight:bold;">(Best Paper Award)</span></div>
        <div class="pub-links">
            <a href="https://dl.acm.org/doi/10.1145/3476886.3477512" target="_blank">Paper</a>
        </div>
    </div>

    <div class="pub-item">
        <span class="pub-title">Elastic Resource Sharing for Distributed Deep Learning</span>
        <div class="pub-authors">Changho Hwang, <strong>Taehyun Kim</strong>, Sunghyun Kim, Jinwoo Shin, KyoungSoo Park</div>
        <div class="pub-venue">USENIX NSDI 2021</div>
        <div class="pub-links">
            <a href="https://www.usenix.org/conference/nsdi21/presentation/hwang" target="_blank">Paper</a>
        </div>
    </div>

    <div class="pub-item">
        <span class="pub-title">CaveBat: Efficient Multi-user Privacy-Preserving Inference for Neural Network-based Recommender Systems</span>
        <div class="pub-authors"><strong>Taehyun Kim</strong>, et al.</div>
        <div class="pub-venue">Under Review / Preprint</div>
        <p class="pub-desc" style="font-size: 0.9rem; color: #666; margin-top: 5px;">
            Proposed a privacy-preserving recommender system using <strong>SERS protocol</strong> and <strong>Homomorphic Encryption</strong>. Achieved <strong>3.1x</strong> computational efficiency and <strong>7.1x</strong> lower latency compared to SOTA 2PC-NN frameworks.
        </p>
    </div>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2><div class="project-category">
        <h3 style="border-bottom: 2px solid #eee; padding-bottom: 10px; margin-bottom: 20px;">Industry Projects @ MangoBoost</h3>
        
        <div class="timeline-item" style="border-left: 4px solid #2ecc71;">
            <h4 class="timeline-title">DPU-based Storage & AI Acceleration</h4>
            <p>Led the development and productization of storage offloading on DPU (ARM SoC + FPGA) and AI accelaration.</p>
            <ul class="skill-list" style="margin-top: 10px;">
                <li><strong>NVMe-oF (TCP) Initiator Offload:</strong> Developed SW/HW co-design architecture utilizing <strong>SPDK</strong> on ARM cores. Achieved line-rate performance and commercialized the solution.</li>
                <li><strong>AI Storage Acceleration:</strong> Developed <strong>Direct Data Path</strong> technology (equivalent to NVIDIA GDS) connecting Storage/DPU to Host GPUs. Integrated with <strong>vLLM, DeepSpeed, and lmcache</strong> to maximize AI inference/training throughput.</li>
                <li><strong>DPU-accelerated Storage Appliance:</strong> Spearheaded the architecture of a high-performance and cost-efficient storage appliance powered by DPU acceleration.</li>
            </ul>
        </div>

        <div class="timeline-item" style="border-left: 4px solid #2ecc71;">
            <h4 class="timeline-title">Host-DPU In-Band Interconnect</h4>
            <p>Developed a proprietary in-band management solution using <strong>virtio</strong> over PCIe.</p>
            <ul class="skill-list" style="margin-top: 10px;">
                <li>Eliminated the need for external physical cables by implementing virtual Ethernet and Serial Console interfaces.</li>
                <li>Designed a whole system and Developed software stack including Linux kernel modules and user-space utilities.</li>
            </ul>
        </div>
    </div>

    <div class="project-category" style="margin-top: 40px;">
        <h3 style="border-bottom: 2px solid #eee; padding-bottom: 10px; margin-bottom: 20px;">Research Projects</h3>

        <div class="timeline-item" style="border-left: 4px solid #3498db;">
            <h4 class="timeline-title">IO-TCP (SmartNIC Networking Stack)</h4>
            <p>Rearchitected the TCP stack to offload I/O operations to SmartNICs (BlueField-2). Decoupled Control/Data planes to achieve <strong>line rate</strong> throughput on a single core.</p>
        </div>

        <div class="timeline-item" style="border-left: 4px solid #3498db;">
            <h4 class="timeline-title">CoDDL (Elastic AI Infrastructure)</h4>
            <p>Built a distributed training framework supporting <strong>seamless scale-out/in</strong>. Improved cluster efficiency by <strong>3.1x</strong> via custom MPI/NCCL scheduling.</p>
        </div>

        <div class="timeline-item" style="border-left: 4px solid #3498db;">
            <h4 class="timeline-title">Large-Scale GNN Training Optimization</h4>
            <p>Addressed memory/bandwidth bottlenecks in training billion-scale graphs.</p>
            <ul class="skill-list" style="margin-top: 10px;">
                <li>Proposed a <strong>locality-aware partial execution</strong> strategy, offloading aggregation tasks to the CPU to mitigate PCIe bottlenecks.</li>
                <li>Optimized load balancing between CPU and GPU, achieving up to <strong>6.6x speedup</strong> in training throughput.</li>
            </ul>
        </div>

        <div class="timeline-item" style="border-left: 4px solid #3498db;">
            <h4 class="timeline-title">CaveBat: Privacy-Preserving GNN Inference</h4>
            <p>Designed a secure recommender system enabling inference on private data without leakage.</p>
            <ul class="skill-list" style="margin-top: 10px;">
                <li>Developed <strong>SERS (Secure Referencing of Private Server Data)</strong> protocol using Homomorphic Encryption and PIR.</li>
                <li>Implemented reference count obfuscation and partial reuse techniques, improving efficiency by <strong>3.1x</strong>.</li>
            </ul>
        </div>
    </div>
</section>
