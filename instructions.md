export default function JiaweiAcademicHomepage() {
  const news = [
    {
      date: "2026-05",
      text: "Joining HKUST(GZ) as a tenure-track Assistant Professor in Intelligent Transportation.",
    },
    {
      date: "2026-01",
      text: "Two papers accepted to ICLR 2026: ELLMob and TrajFlow.",
    },
    {
      date: "2024-12",
      text: "Our paper on LLM agents for personal mobility generation was presented at NeurIPS 2024.",
    },
  ];

  const pubGroups = [
    {
      title: "Mobility Generation and Cognition with Foundation Models",
      subtitle:
        "Large language models for human mobility generation, event-aware behavior modeling, and urban cognition.",
      papers: [
        {
          title:
            "Large language models as urban residents: An LLM agent framework for personal mobility generation",
          venue: "NeurIPS 2024",
          authors: "Jiawei Wang, et al.",
          desc:
            "Behaviorally grounded LLM agents for simulating personal mobility in cities.",
        },
        {
          title:
            "ELLMob: Event-Driven Human Mobility Generation with Self-Aligned LLM Framework",
          venue: "ICLR 2026",
          authors: "Jiawei Wang, et al.",
          desc:
            "An event-aware self-aligned LLM framework for human mobility generation under dynamic urban contexts.",
        },
      ],
    },
    {
      title: "Generative Modeling for Traffic Simulation",
      subtitle:
        "Generative AI methods for traffic simulation, trajectory synthesis, and transportation system modeling.",
      papers: [
        {
          title:
            "TrajFlow: Nation-wide Pseudo GPS Trajectory Generation with Flow Matching Models",
          venue: "ICLR 2026",
          authors: "Jiawei Wang, et al.",
          desc:
            "A flow matching framework for large-scale pseudo GPS trajectory generation at national scale.",
        },
        {
          title:
            "Traffic speed prediction for urban transportation network: A path-based deep learning approach",
          venue: "Transportation Research Part C 2019",
          authors: "Jiawei Wang, et al.",
          desc:
            "A path-based deep learning approach for network-level urban traffic state modeling.",
        },
        {
          title:
            "Understanding the daily operations of electric taxis: From macro-patterns to micro-behaviors",
          venue: "Transportation Research Part D 2024",
          authors: "Jiawei Wang, et al.",
          desc:
            "A data-driven analysis of electric taxi operations from citywide patterns to fine-grained behavioral dynamics.",
        },
      ],
    },
    {
      title: "Reinforcement Learning for Public Transportation Control",
      subtitle:
        "Learning-based control and optimization for bus operations, transit reliability, and coordinated mobility systems.",
      papers: [
        {
          title:
            "Dynamic holding control to avoid bus bunching: A multi-agent deep reinforcement learning framework",
          venue: "Transportation Research Part C 2020",
          authors: "Jiawei Wang, et al.",
          desc:
            "A multi-agent deep RL framework for adaptive bus holding control.",
        },
        {
          title:
            "Reducing bus bunching with asynchronous multi-agent reinforcement learning",
          venue: "IJCAI 2021",
          authors: "Jiawei Wang, et al.",
          desc:
            "Asynchronous multi-agent reinforcement learning for robust bus bunching mitigation.",
        },
        {
          title:
            "Robust dynamic bus control: A distributional multi-agent reinforcement learning approach",
          venue: "IEEE TITS 2022",
          authors: "Jiawei Wang, et al.",
          desc:
            "Distributional multi-agent RL for robust transit control under uncertainty.",
        },
        {
          title:
            "Multi-objective multi-agent deep reinforcement learning to reduce bus bunching for multi-line services with a shared corridor",
          venue: "Transportation Research Part C 2023",
          authors: "Jiawei Wang, et al.",
          desc:
            "Multi-objective RL for coordinated control in multi-line bus systems.",
        },
      ],
    },
  ];

  const experience = [
    {
      role: "Incoming Assistant Professor",
      org: "HKUST (Guangzhou)",
      time: "May 2026 – Future",
      desc: "Building a research program on Generative Intelligent Transportation.",
    },
    {
      role: "Postdoctoral Researcher",
      org: "Graduate School of Interdisciplinary Information Studies, The University of Tokyo",
      time: "2023 – Present",
      desc: "Research on AI for transportation, mobility generation, and traffic simulation.",
    },
    {
      role: "Visiting Scholar",
      org: "Center for Spatial Information Science, The University of Tokyo",
      time: "2023 – Present",
      desc: "Research on urban mobility intelligence and spatial data-driven transport modeling.",
    },
    {
      role: "Ph.D. in Civil Engineering",
      org: "McGill University",
      time: "2019 – 2023",
      desc: "Transportation systems, reinforcement learning, and mobility operations.",
    },
    {
      role: "M.Eng. in Traffic Information Engineering and Control",
      org: "Sun Yat-sen University",
      time: "2016 – 2019",
      desc: "Transportation data analysis and intelligent transportation systems.",
    },
    {
      role: "B.Eng. in Transportation Engineering",
      org: "Sun Yat-sen University",
      time: "2012 – 2016",
      desc: "Foundations in transportation engineering and systems analysis.",
    },
  ];

  return (
    <div className="min-h-screen bg-white text-neutral-900">
      <header className="sticky top-0 z-20 border-b border-neutral-200 bg-white/90 backdrop-blur">
        <div className="mx-auto flex max-w-7xl items-center justify-between px-6 py-4 lg:px-8">
          <a href="#top" className="text-lg font-semibold tracking-tight text-neutral-950">
            Jiawei Wang
          </a>
          <nav className="hidden gap-6 text-sm text-neutral-600 md:flex">
            <a href="#about" className="transition hover:text-neutral-950">About</a>
            <a href="#news" className="transition hover:text-neutral-950">News</a>
            <a href="#research" className="transition hover:text-neutral-950">Research</a>
            <a href="#experience" className="transition hover:text-neutral-950">Experience</a>
          </nav>
        </div>
      </header>

      <main id="top" className="mx-auto grid max-w-7xl grid-cols-1 gap-12 px-6 py-10 lg:grid-cols-[300px_minmax(0,1fr)] lg:px-8">
        <aside className="lg:sticky lg:top-24 lg:self-start">
          <div className="overflow-hidden rounded-3xl border border-neutral-200 bg-white shadow-sm">
            <img
              src="/个人图片.png"
              alt="Jiawei Wang"
              className="aspect-[4/5] w-full object-cover object-center"
            />
            <div className="space-y-5 p-6">
              <div>
                <h1 className="text-3xl font-bold tracking-tight text-neutral-950">Jiawei Wang</h1>
                <p className="mt-2 text-base text-neutral-700">
                  Incoming Assistant Professor in Intelligent Transportation
                </p>
                <p className="mt-1 text-sm text-neutral-500">HKUST (Guangzhou)</p>
              </div>

              <div className="space-y-2 text-sm leading-6 text-neutral-600">
                <p>Postdoctoral Researcher, The University of Tokyo</p>
                <p>Visiting Scholar, CSIS, The University of Tokyo</p>
                <p>AI for Transportation · Generative Intelligent Transportation</p>
              </div>

              <div className="rounded-2xl bg-neutral-50 p-4 text-sm leading-6 text-neutral-700">
                <p className="font-medium text-neutral-950">Research keywords</p>
                <p className="mt-2">
                  LLMs for Mobility · Flow Matching · Generative Traffic Simulation · Reinforcement Learning · Transit Control
                </p>
              </div>

              <div className="flex flex-wrap gap-2 text-sm">
                <a
                  className="rounded-full border border-neutral-300 px-3 py-1.5 transition hover:bg-neutral-100"
                  href="https://scholar.google.com/citations?hl=zh-CN&user=Y1gU9wYAAAAJ"
                >
                  Google Scholar
                </a>
                <a
                  className="rounded-full border border-neutral-300 px-3 py-1.5 transition hover:bg-neutral-100"
                  href="https://github.com/Wangjw6"
                >
                  GitHub
                </a>
                <a
                  className="rounded-full border border-neutral-300 px-3 py-1.5 transition hover:bg-neutral-100"
                  href="https://www.linkedin.com/in/its-jiawei-wang"
                >
                  LinkedIn
                </a>
              </div>
            </div>
          </div>
        </aside>

        <section className="space-y-12">
          <section id="about" className="rounded-3xl border border-neutral-200 bg-white p-8 shadow-sm">
            <h2 className="text-2xl font-semibold tracking-tight text-neutral-950">About</h2>
            <div className="mt-5 space-y-4 text-[15px] leading-7 text-neutral-700">
              <p>
                Jiawei Wang is an incoming tenure-track Assistant Professor in Intelligent Transportation at the Systems Hub,
                HKUST (Guangzhou), where he will join in May 2026. He is currently a Postdoctoral Researcher at the Graduate
                School of Interdisciplinary Information Studies, The University of Tokyo, and a Visiting Scholar at the Center
                for Spatial Information Science.
              </p>
              <p>
                He received his Ph.D. in Civil Engineering from McGill University. Prior to that, he obtained his B.Eng. in
                Transportation Engineering and M.Eng. in Traffic Information Engineering and Control from Sun Yat-sen University.
              </p>
              <p>
                His research lies at the intersection of artificial intelligence and transportation systems, with a particular
                interest in building an integrated scientific route from <span className="font-medium text-neutral-950">traffic generation</span>
                , to <span className="font-medium text-neutral-950">traffic cognition</span>, and further to
                <span className="font-medium text-neutral-950"> traffic control</span>. He develops data-driven and behaviorally grounded
                methods for mobility generation, generative traffic simulation, and public transportation optimization.
              </p>
            </div>
          </section>

          <section id="news" className="rounded-3xl border border-neutral-200 bg-white p-8 shadow-sm">
            <div className="flex items-center justify-between gap-4">
              <h2 className="text-2xl font-semibold tracking-tight text-neutral-950">News</h2>
              <span className="text-sm text-neutral-500">Selected updates</span>
            </div>
            <div className="mt-6 space-y-4">
              {news.map((item) => (
                <div key={item.date + item.text} className="flex gap-4 rounded-2xl border border-neutral-100 p-4">
                  <div className="min-w-[84px] text-sm font-medium text-neutral-500">[{item.date}]</div>
                  <p className="text-[15px] leading-7 text-neutral-700">{item.text}</p>
                </div>
              ))}
            </div>
          </section>

          <section id="research" className="rounded-3xl border border-neutral-200 bg-white p-8 shadow-sm">
            <div className="flex items-center justify-between gap-4">
              <h2 className="text-2xl font-semibold tracking-tight text-neutral-950">Research</h2>
              <a
                href="https://scholar.google.com/citations?hl=zh-CN&user=Y1gU9wYAAAAJ&view_op=list_works&sortby=pubdate"
                className="text-sm text-neutral-500 transition hover:text-neutral-950"
              >
                Full publication list
              </a>
            </div>

            <div className="mt-8 space-y-8">
              {pubGroups.map((group) => (
                <section key={group.title} className="rounded-2xl border border-neutral-100 p-6">
                  <h3 className="text-xl font-semibold tracking-tight text-neutral-950">{group.title}</h3>
                  <p className="mt-2 text-[15px] leading-7 text-neutral-600">{group.subtitle}</p>
                  <div className="mt-5 space-y-4">
                    {group.papers.map((paper) => (
                      <article key={paper.title} className="rounded-2xl bg-neutral-50 p-5">
                        <h4 className="text-lg font-medium leading-7 text-neutral-950">{paper.title}</h4>
                        <p className="mt-1 text-sm font-medium text-neutral-500">{paper.venue}</p>
                        <p className="mt-2 text-sm text-neutral-600">{paper.authors}</p>
                        <p className="mt-3 text-[15px] leading-7 text-neutral-700">{paper.desc}</p>
                        <div className="mt-4 flex flex-wrap gap-3 text-sm text-neutral-600">
                          <a href="#" className="underline underline-offset-4">PDF</a>
                          <a href="#" className="underline underline-offset-4">Code</a>
                          <a href="#" className="underline underline-offset-4">BibTeX</a>
                        </div>
                      </article>
                    ))}
                  </div>
                </section>
              ))}
            </div>
          </section>

          <section id="experience" className="rounded-3xl border border-neutral-200 bg-white p-8 shadow-sm">
            <h2 className="text-2xl font-semibold tracking-tight text-neutral-950">Experience</h2>
            <div className="mt-6 space-y-5">
              {experience.map((item) => (
                <div key={item.role + item.org} className="rounded-2xl border border-neutral-100 p-5">
                  <div className="flex flex-col gap-1 md:flex-row md:items-center md:justify-between">
                    <h3 className="text-lg font-semibold text-neutral-950">{item.role}</h3>
                    <p className="text-sm text-neutral-500">{item.time}</p>
                  </div>
                  <p className="mt-1 text-sm font-medium text-neutral-600">{item.org}</p>
                  <p className="mt-3 text-[15px] leading-7 text-neutral-700">{item.desc}</p>
                </div>
              ))}
            </div>
          </section>
        </section>
      </main>
    </div>
  );
}
