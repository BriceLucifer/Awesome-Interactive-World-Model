<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome Interactive World Model</title>
    <style>
        :root {
            --bg: #0d1117;
            --card-bg: #161b22;
            --border: #30363d;
            --text: #e6edf3;
            --text-secondary: #8b949e;
            --accent: #58a6ff;
            --tag-open: #3fb950;
            --tag-closed: #f85149;
            --tag-star: #f0c000;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background: var(--bg);
            color: var(--text);
            min-height: 100vh;
        }

        .header {
            text-align: center;
            padding: 48px 20px 32px;
            border-bottom: 1px solid var(--border);
        }

        .header h1 {
            font-size: 2.2rem;
            margin-bottom: 8px;
            background: linear-gradient(135deg, #58a6ff, #bc8cff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .header p {
            color: var(--text-secondary);
            font-size: 0.95rem;
            margin-bottom: 6px;
        }

        .legend {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 12px;
            font-size: 0.85rem;
            color: var(--text-secondary);
            flex-wrap: wrap;
        }

        .legend span { display: flex; align-items: center; gap: 4px; }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 24px 20px 60px;
        }

        /* Search & Filters */
        .search-bar {
            position: sticky;
            top: 0;
            z-index: 10;
            background: var(--bg);
            padding: 16px 0;
        }

        .search-bar input {
            width: 100%;
            padding: 12px 16px;
            border-radius: 8px;
            border: 1px solid var(--border);
            background: var(--card-bg);
            color: var(--text);
            font-size: 1rem;
            outline: none;
            transition: border-color 0.2s;
        }

        .search-bar input:focus { border-color: var(--accent); }

        .filters {
            display: flex;
            gap: 8px;
            margin-top: 12px;
            flex-wrap: wrap;
        }

        .filter-btn {
            padding: 6px 14px;
            border-radius: 20px;
            border: 1px solid var(--border);
            background: transparent;
            color: var(--text-secondary);
            font-size: 0.82rem;
            cursor: pointer;
            transition: all 0.2s;
        }

        .filter-btn:hover { border-color: var(--accent); color: var(--accent); }
        .filter-btn.active { background: var(--accent); color: #fff; border-color: var(--accent); }

        /* Sections */
        .section { margin-top: 32px; }

        .section-title {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 14px;
            padding-bottom: 8px;
            border-bottom: 1px solid var(--border);
            color: var(--accent);
        }

        .subsection-title {
            font-size: 1.05rem;
            font-weight: 600;
            margin: 18px 0 10px 8px;
            color: #bc8cff;
        }

        .target-note {
            font-size: 0.9rem;
            color: var(--text-secondary);
            margin: 8px 0 10px 8px;
            font-style: italic;
        }

        /* Paper Cards */
        .paper-card {
            display: flex;
            align-items: flex-start;
            gap: 12px;
            padding: 14px 16px;
            border-radius: 8px;
            border: 1px solid var(--border);
            background: var(--card-bg);
            margin-bottom: 8px;
            transition: border-color 0.2s, transform 0.15s;
            text-decoration: none;
            color: inherit;
        }

        .paper-card:hover {
            border-color: var(--accent);
            transform: translateX(4px);
        }

        .paper-tags {
            display: flex;
            gap: 6px;
            flex-shrink: 0;
            padding-top: 2px;
        }

        .tag {
            font-size: 0.72rem;
            padding: 2px 8px;
            border-radius: 12px;
            font-weight: 600;
            white-space: nowrap;
        }

        .tag-open { background: rgba(63,185,80,0.15); color: var(--tag-open); }
        .tag-closed { background: rgba(248,81,73,0.15); color: var(--tag-closed); }
        .tag-star { background: rgba(240,192,0,0.12); color: var(--tag-star); }

        .paper-info { flex: 1; min-width: 0; }

        .paper-title {
            font-size: 0.95rem;
            font-weight: 500;
            line-height: 1.4;
            word-break: break-word;
        }

        .paper-note {
            font-size: 0.8rem;
            color: var(--text-secondary);
            margin-top: 4px;
        }

        .paper-link {
            font-size: 0.75rem;
            color: var(--accent);
            opacity: 0.7;
            margin-top: 2px;
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap;
        }

        .no-results {
            text-align: center;
            color: var(--text-secondary);
            padding: 48px 0;
            font-size: 1.1rem;
        }

        .stats {
            text-align: center;
            color: var(--text-secondary);
            font-size: 0.82rem;
            margin-top: 8px;
        }

        .hidden { display: none !important; }

        @media (max-width: 600px) {
            .header h1 { font-size: 1.5rem; }
            .paper-card { flex-direction: column; gap: 8px; }
        }
    </style>
</head>
<body>

<div class="header">
    <h1>🌍 Awesome Interactive World Model</h1>
    <p>A curated list of papers on Interactive World Models</p>
    <div class="legend">
        <span>🌟 Classic</span>
        <span style="color:var(--tag-open)">✅ Open Source</span>
        <span style="color:var(--tag-closed)">❌ Not Open Source</span>
    </div>
</div>

<div class="container">
    <div class="search-bar">
        <input type="text" id="searchInput" placeholder="🔍 Search papers by title, note, or category..." autofocus>
        <div class="filters" id="filterContainer">
            <button class="filter-btn active" data-filter="all">All</button>
            <button class="filter-btn" data-filter="open">✅ Open Source</button>
            <button class="filter-btn" data-filter="closed">❌ Not Open Source</button>
            <button class="filter-btn" data-filter="star">🌟 Classic</button>
        </div>
        <div class="stats" id="statsDisplay"></div>
    </div>
    <div id="paperList"></div>
</div>

<script>
const PAPERS = [
    // ===== General World Model =====
    { section: "General World Model", title: "Lingbot-World: Advancing Open-source World Models", url: "https://arxiv.org/abs/2601.20540", open: true, star: true, note: "分钟级别Memory" },
    { section: "General World Model", title: "Matrix-game 2.0: An open-source real-time and streaming interactive world model", url: "https://arxiv.org/abs/2508.13009", open: true, star: true, note: "首个开源实时交互World Model" },
    { section: "General World Model", title: "Yan: Foundational Interactive Video Generation", url: "https://arxiv.org/abs/2508.08601", open: false, star: false },
    { section: "General World Model", title: "Genie: Generative Interactive Environments", url: "https://arxiv.org/abs/2402.15391", open: false, star: false },
    { section: "General World Model", title: "Yume-1.5: A Text-Controlled Interactive World Generation Model", url: "https://arxiv.org/abs/2512.22096", open: true, star: false },
    { section: "General World Model", title: "RELIC: Interactive Video World Model with Long-Horizon Memory", url: "https://arxiv.org/abs/2512.04040", open: false, star: false },
    { section: "General World Model", title: "Hunyuan-GameCraft-2: Instruction-following Interactive Game World Model", url: "https://arxiv.org/abs/2511.23429", open: false, star: false },
    { section: "General World Model", title: "Hunyuan-GameCraft: High-dynamic Interactive Game Video Generation with Hybrid History Condition", url: "https://arxiv.org/abs/2506.17201", open: true, star: false },
    { section: "General World Model", title: "HY-World 1.5: A Systematic Framework for Interactive World Modeling with Real-Time Latency and Geometric Consistency", url: "https://3d-models.hunyuan.tencent.com/world/world1_5/HYWorld_1.5_Tech_Report.pdf", open: true, star: false },
    { section: "General World Model", title: "Astra: General Interactive World Model with Autoregressive Denoising", url: "https://arxiv.org/abs/2512.08931", open: true, star: false },
    { section: "General World Model", title: "PAN: A World Model for General, Interactable, and Long-Horizon World Simulation", url: "https://arxiv.org/abs/2511.09057", open: false, star: false },

    // ===== Dataset and Benchmark =====
    { section: "Dataset and Benchmark", title: "MIND: Benchmarking Memory Consistency and Action Control in World Models", url: "https://arxiv.org/abs/2602.08025", open: true, star: true, note: "首个 Open Domain Memory和Action Benchmark" },
    { section: "Dataset and Benchmark", title: "WorldScore: A Unified Evaluation Benchmark for World Generation", url: "https://arxiv.org/abs/2504.00983", open: true, star: false },
    { section: "Dataset and Benchmark", title: "WorldModelBench: Judging Video Generation Models As World Models", url: "https://arxiv.org/abs/2502.20694", open: true, star: false },
    { section: "Dataset and Benchmark", title: "WorldSimBench: Towards Video Generation Models as World Simulators", url: "https://arxiv.org/abs/2410.18072", open: true, star: false },
    { section: "Dataset and Benchmark", title: "Toward Memory-Aided World Models: Benchmarking via Spatial Consistency", url: "https://arxiv.org/abs/2505.22976", open: true, star: false },

    // ===== Long Video Generation =====
    { section: "Long Video Generation", title: "Causal Forcing: Autoregressive Diffusion Distillation Done Right for High-Quality Real-Time Interactive Video Generation", url: "https://arxiv.org/abs/2602.02214", open: true, star: true, note: "ODE视角" },
    { section: "Long Video Generation", title: "Self-Forcing++: Towards Minute-Scale High-Quality Video Generation", url: "https://arxiv.org/abs/2510.02283", open: false, star: true, note: "解决了sf的问题" },
    { section: "Long Video Generation", title: "Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion", url: "https://arxiv.org/abs/2506.08009", open: true, star: true, note: "DMD视角" },
    { section: "Long Video Generation", title: "Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion", url: "https://arxiv.org/abs/2407.01392", open: true, star: true, note: "训练技巧" },
    { section: "Long Video Generation", title: "From Slow Bidirectional to Fast Autoregressive Video Diffusion Models", url: "https://arxiv.org/abs/2412.07772v4", open: true, star: true, note: "Teacher->Student加速" },
    { section: "Long Video Generation", title: "Frame Context Packing and Drift Prevention in Next-Frame-Prediction Video Diffusion Models", url: "https://arxiv.org/abs/2504.12626", open: true, star: true, note: "压缩上下文" },
    { section: "Long Video Generation", title: "Pretraining Frame Preservation in Autoregressive Video Memory Compression", url: "https://arxiv.org/abs/2512.23851", open: false, star: true, note: "压缩恢复训练" },
    { section: "Long Video Generation", title: "Context Forcing: Consistent Autoregressive Video Generation with Long Context", url: "https://arxiv.org/abs/2602.06028", open: false, star: false },
    { section: "Long Video Generation", title: "Reward Forcing: Efficient Streaming Video Generation with Rewarded Distribution Matching Distillation", url: "https://arxiv.org/abs/2512.04678", open: true, star: false },
    { section: "Long Video Generation", title: "Latent Forcing: Reordering the Diffusion Trajectory for Pixel-Space Image Generation", url: "https://arxiv.org/abs/2602.11401", open: true, star: false },
    { section: "Long Video Generation", title: "FAR: Frame Autoregressive Model for Both Short- and Long-Context Video Modeling", url: "https://arxiv.org/abs/2503.19325", open: true, star: false },
    { section: "Long Video Generation", title: "Rolling Forcing: Autoregressive Long Video Diffusion in Real Time", url: "https://arxiv.org/abs/2509.25161", open: true, star: false },
    { section: "Long Video Generation", title: "Mode Seeking meets Mean Seeking for Fast Long Video Generation", url: "https://arxiv.org/abs/2602.24289", open: false, star: false },
    { section: "Long Video Generation", title: "Memory Forcing: Spatio-Temporal Memory for Consistent Scene Generation on Minecraft", url: "https://arxiv.org/abs/2510.03198", open: false, star: false },

    // ===== Memory Consistency =====
    { section: "Memory Consistency", title: "Context as Memory: Scene-Consistent Interactive Long Video Generation with Memory Retrieval", url: "https://arxiv.org/abs/2506.03141", open: false, star: true, note: "w/Pose FOV重叠检索 Memory" },
    { section: "Memory Consistency", title: "VMem: Consistent Interactive Video Scene Generation with Surfel-Indexed View Memory", url: "https://arxiv.org/abs/2506.18903", open: true, star: false },
    { section: "Memory Consistency", title: "Video World Models with Long-term Spatial Memory", url: "https://arxiv.org/abs/2506.05284", open: false, star: false },
    { section: "Memory Consistency", title: "StableWorld: Towards Stable and Consistent Long Interactive Video Generation", url: "https://arxiv.org/abs/2601.15281", open: true, star: false },
    { section: "Memory Consistency", title: "Infinite-World: Scaling Interactive World Models to 1000-Frame Horizons via Pose-Free Hierarchical Memory", url: "https://arxiv.org/abs/2602.02393", open: true, star: true, note: "Pose-Free Memory" },
    { section: "Memory Consistency", title: "AnchorWeave: World-Consistent Video Generation with Retrieved Local Spatial Memories", url: "https://arxiv.org/abs/2602.14941", open: true, star: false },
    { section: "Memory Consistency", title: "Flow Equivariant World Models: Structured Dynamics Outside the Field of View", url: "https://arxiv.org/abs/2601.01075", open: true, star: true, note: "首个视野外Dynamic Memory的World Model" },

    // ===== Action Control =====
    { section: "Action Control", subsection: "Action Control Generalization", title: "Olaf-World: Orienting Latent Actions for Video World Modeling", url: "https://arxiv.org/abs/2602.10104", open: false, star: true, note: "迁移技能" },
    { section: "Action Control", subsection: "Action Control Generalization", title: "AdaWorld: Learning Adaptable World Models with Latent Actions", url: "https://arxiv.org/abs/2503.18938", open: true, star: true, note: "不再受限于固定的控制" },
    { section: "Action Control", subsection: "Action Control Generalization", title: "GameFactory: Creating New Games with Generative Interactive Videos", url: "https://arxiv.org/abs/2501.08325", open: false, star: true, note: "从游戏中获取动作控制的能力" },

    // ===== Interactive =====
    { section: "Interactive", title: "Spatia: Video Generation with Updatable Spatial Memory", url: "https://arxiv.org/abs/2512.15716", open: false, star: true, note: "编辑物体，添加/消失/变色等" },
    { section: "Interactive", title: "Hunyuan-GameCraft-2: Instruction-following Interactive Game World Model", url: "https://arxiv.org/abs/2511.23429", open: false, star: true, note: "文本交互：变枪、刀等出来，可以影响环境等" },

    // ===== Multi-People =====
    { section: "Multi-People", title: "Solaris: Building a Multiplayer Video World Model in Minecraft", url: "https://arxiv.org/abs/2602.22208", open: true, star: true, note: "首个多人Minecraft World Model" },

    // ===== Post-Training =====
    { section: "Post-Training", title: "RLVR-World: Training World Models with Reinforcement Learning", url: "https://arxiv.org/abs/2505.13934", open: true, star: false },
    { section: "Post-Training", title: "WorldCompass: Reinforcement Learning for Long-Horizon World Models", url: "https://arxiv.org/abs/2602.09022", open: false, star: false },

    // ===== Physic =====
    { section: "Physic", title: "RealWonder: Real-Time Physical Action-Conditioned Video Generation", url: "https://arxiv.org/abs/2603.05449", open: true, star: false },
];

const SECTION_ORDER = [
    "General World Model",
    "Dataset and Benchmark",
    "Long Video Generation",
    "Memory Consistency",
    "Action Control",
    "Interactive",
    "Multi-People",
    "Post-Training",
    "Physic",
];

const searchInput = document.getElementById("searchInput");
const paperListElement = document.getElementById("paperList");
const statsDisplay = document.getElementById("statsDisplay");
const filterButtons = document.querySelectorAll(".filter-btn");

let activeFilter = "all";

function renderPapers() {
    const query = searchInput.value.toLowerCase().trim();
    let visibleCount = 0;

    const grouped = {};
    SECTION_ORDER.forEach(sectionName => { grouped[sectionName] = []; });

    PAPERS.forEach(paper => {
        // Filter
        if (activeFilter === "open" && !paper.open) return;
        if (activeFilter === "closed" && paper.open) return;
        if (activeFilter === "star" && !paper.star) return;

        // Search
        if (query) {
            const haystack = [
                paper.title,
                paper.note || "",
                paper.section,
                paper.subsection || "",
            ].join(" ").toLowerCase();
            if (!haystack.includes(query)) return;
        }

        grouped[paper.section].push(paper);
        visibleCount++;
    });

    let html = "";

    SECTION_ORDER.forEach(sectionName => {
        const papers = grouped[sectionName];
        if (papers.length === 0) return;

        html += `<div class="section"><div class="section-title">${sectionName}</div>`;

        let currentSubsection = null;
        papers.forEach(paper => {
            if (paper.subsection && paper.subsection !== currentSubsection) {
                currentSubsection = paper.subsection;
                html += `<div class="subsection-title">${currentSubsection}</div>`;
            }

            const tags = [];
            if (paper.star) tags.push('<span class="tag tag-star">🌟 Classic</span>');
            tags.push(paper.open
                ? '<span class="tag tag-open">✅ Open</span>'
                : '<span class="tag tag-closed">❌ Closed</span>'
            );

            html += `
                <a class="paper-card" href="${paper.url}" target="_blank" rel="noopener">
                    <div class="paper-tags">${tags.join("")}</div>
                    <div class="paper-info">
                        <div class="paper-title">${highlightMatch(paper.title, query)}</div>
                        ${paper.note ? `<div class="paper-note">${highlightMatch(paper.note, query)}</div>` : ""}
                        <div class="paper-link">${paper.url}</div>
                    </div>
                </a>`;
        });

        if (sectionName === "Action Control") {
            html += `<div class="subsection-title">Action Space Generalization</div>`;
            html += `<div class="target-note">Target: 控制移动速度快慢 (None now)</div>`;
        }

        html += `</div>`;
    });

    if (visibleCount === 0) {
        html = `<div class="no-results">No papers found matching your search 🔍</div>`;
    }

    paperListElement.innerHTML = html;
    statsDisplay.textContent = `Showing ${visibleCount} of ${PAPERS.length} papers`;
}

function highlightMatch(text, query) {
    if (!query) return text;
    const escapedQuery = query.replace(/[.*+?^${}()|[\]\\]/g, "\\$&");
    return text.replace(new RegExp(`(${escapedQuery})`, "gi"), '<mark style="background:#58a6ff33;color:#58a6ff;border-radius:2px;padding:0 2px">$1</mark>');
}

// Event listeners
searchInput.addEventListener("input", renderPapers);

filterButtons.forEach(button => {
    button.addEventListener("click", () => {
        filterButtons.forEach(btn => btn.classList.remove("active"));
        button.classList.add("active");
        activeFilter = button.dataset.filter;
        renderPapers();
    });
});

// Initial render
renderPapers();
</script>

</body>
</html>
