---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/2026 JPR CV Full [ENG].pdf
      headings:
        about: About me
        education: Education
        interests: Research Interests
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      spacing:
        padding: ["0px", "0", "0px", "0"]
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: xs # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: markdown
    id: research
    content:
      title: '📚 Research Overview'
      subtitle: ''
      text: |-
        My research focuses on developing **flexible, stretchable, and wearable electronic systems** enabled by advanced micro- and nanofabrication technologies. The objective is to bridge semiconductor manufacturing with emerging applications in wearable healthcare, energy harvesting, and intelligent electronic systems.

        My primary research areas include:

        - **Flexible and Stretchable Electronics:** Development of mechanically compliant electronic architectures using serpentine, origami, and kirigami-inspired designs to improve reliability under bending and stretching.

        - **Thermoelectric Energy Harvesting:** Design and fabrication of flexible thermoelectric generators for self-powered wearable sensing systems and low-power IoT applications.

        - **Micro- and Nanofabrication:** CMOS-compatible fabrication processes, MEMS technologies, thin-film devices, flexible hybrid electronics, and advanced semiconductor manufacturing.

        - **AI for Electronic Design:** Artificial intelligence and optimization algorithms for PCB autorouting, electronic design automation, and intelligent circuit design.

        I welcome collaborations with researchers, industry partners, and students interested in flexible electronics, wearable sensing, semiconductor manufacturing, and intelligent electronic systems.
    design:
      columns: '2'
  
  - block: markdown
    id: papers
    content:
      title: Featured Publications
      subtitle: Representative publications highlighting my research in flexible electronics, wearable sensing, thermoelectric energy harvesting, and advanced semiconductor manufacturing.
      text: |-

        #### Design and Evaluation of LET-Based Soft Hinges for Stress Mitigation in Flexible Copper Interconnects
        ***Flexible and Printed Electronics***, 2025  
        Introduces LET-based soft hinges to reduce stress concentration in flexible copper interconnects, improving the mechanical reliability of flexible printed electronics. **[IOP Science](https://doi.org/10.1088/2058-8585/ae0653)**

        ---
        #### Self-Powered End-to-End Wireless Sensor Network for Geophysical Explorations
        ***IEEE Systems Journal***, 2025  
        Development of a self-powered wireless sensing platform integrating energy harvesting and low-power electronics for geophysical exploration. **[IEEE Xplore](https://doi.org/10.1109/JSYST.2025.3532698)**

        ---
        #### Beyond Flexible: Unveiling the Next Era of Flexible Electronic Systems
        **Advanced Materials**, 2024  
        Perspective article discussing the evolution of flexible electronic technologies toward intelligent and multifunctional electronic systems. **[Wiley](https://doi.org/10.1002/adma.202406424)**

        ---
        #### Paper-Based Origami Flexible and Foldable Thermoelectric Nanogenerator
        ***Nano Energy***, 2017  
        Demonstrates an origami-inspired paper-based thermoelectric generator capable of lightweight, foldable energy harvesting for wearable applications. **[ScienceDirect](https://doi.org/10.1016/j.nanoen.2016.11.032)**
        
        <br>

        **→ [View complete publication list](/publications/)**

    design:
      columns: "2"
      
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: Latest research updates and publications
      text: |-
        <div class="not-prose rounded-2xl border border-slate-700 bg-slate-900 overflow-hidden shadow-xl">
        <img
          src="/images/news/mxene_teg.jpg"
          alt="MXene-assisted Bi2Te3 thermoelectric generator"
          class="h-[280px] w-full object-cover">
        
        <div class="p-8">

        <div class="flex flex-wrap gap-2 mb-5">
          <span class="rounded-full bg-emerald-900/50 text-emerald-300 px-3 py-1 text-sm font-semibold border border-emerald-700">
            New Publication
          </span>

          <span class="rounded-full bg-cyan-900/50 text-cyan-300 px-3 py-1 text-sm font-semibold border border-cyan-700">
            Thermoelectrics
          </span>

          <span class="rounded-full bg-blue-900/50 text-blue-300 px-3 py-1 text-sm font-semibold border border-blue-700">
            MXene
          </span>
        </div>

        <p class="text-sm text-slate-400 mb-3">
          August 2026 · RSC Advances
        </p>

        <h3 class="text-2xl font-bold text-white mb-4">
          MXene-assisted Bi₂Te₃ pellet-based thermoelectric generator
        </h3>

        <p class="text-slate-300 leading-7 mb-5">
          Our latest work demonstrates how a Ti₃C₂Tₓ MXene interfacial
          layer can enhance the performance of a Bi₂Te₃ pellet-based
          thermoelectric generator, achieving a <strong>13.8% increase
          in open-circuit voltage</strong> and a <strong>32% improvement
          in maximum output power</strong>. The results highlight a
          practical approach toward improved thermoelectric energy
          harvesting for wearable electronics and autonomous sensors.
        </p>

        <p class="text-slate-400 mb-6">
          S. S. Ali, S. Firdous, S. Dieng, <strong>J. P. Rojas</strong>,
          and T. A. Saleh
        </p>

        <div class="flex flex-wrap gap-3">

          <a href="https://doi.org/10.1039/d6ra06939h"
            target="_blank"
            rel="noopener"
            class="inline-flex items-center rounded-lg bg-primary-600 px-4 py-2 text-sm font-semibold text-white hover:bg-primary-500">
            Read Paper →
          </a>

          <a href="/publications/"
            class="inline-flex items-center rounded-lg border border-slate-600 px-4 py-2 text-sm font-semibold text-slate-300 hover:border-slate-400">
            All Publications
          </a>

          </div>

        </div>

        </div>

        <div class="not-prose rounded-2xl border border-slate-700 bg-slate-900 overflow-hidden shadow-xl">
        <img
          src="/images/news/advmat.jpg"
          alt="Adv. Mat top viewed certificate"
          class="h-[280px] w-full object-cover">
        
        <div class="p-8">

        <div class="flex flex-wrap gap-2 mb-5">
          <span class="rounded-full bg-emerald-900/50 text-emerald-300 px-3 py-1 text-sm font-semibold border border-emerald-700">
            Recent Award
          </span>

          <span class="rounded-full bg-cyan-900/50 text-cyan-300 px-3 py-1 text-sm font-semibold border border-cyan-700">
            Benyond Flex. Elect.
          </span>

          <span class="rounded-full bg-blue-900/50 text-blue-300 px-3 py-1 text-sm font-semibold border border-blue-700">
            Adv. Mat.
          </span>
        </div>

        <p class="text-sm text-slate-400 mb-3">
          May 2026 · Advanced Materials
        </p>

        <h3 class="text-2xl font-bold text-white mb-4">
          Honored to see our article, “Beyond Flexible: Unveiling the Next Era of Flexible Electronic Systems,” recognized as a Top Viewed Article 2025 in Advanced Materials.            
        </h3>

        <p class="text-slate-300 leading-7 mb-5">
          Advanced Materials continues to be one of the leading journals in materials science and engineering, bringing together impactful advances across electronics, energy, nanotechnology, and biomedical systems. It is encouraging to see growing interest in the future of flexible and next-generation electronic systems.
          Grateful to all who contributed to this work and to the broader research community for the engagement around this topic.
        </p>

        <div class="flex flex-wrap gap-3">

          <a href="https://doi.org/10.1002/adma.202406424"
            target="_blank"
            rel="noopener"
            class="inline-flex items-center rounded-lg bg-primary-600 px-4 py-2 text-sm font-semibold text-white hover:bg-primary-500">
            Read Paper →
          </a>

          </div>

        </div>

        </div>

    design:
      columns: "1"
  
  
 
---
