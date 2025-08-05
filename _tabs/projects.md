---
icon: fas fa-project-diagram
order: 5
---

<style>
.projects-section {
    margin-bottom: 3rem;
}

.projects-title {
    font-size: 1.5rem;
    font-weight: bold;
    color: #007bff;
    margin-bottom: 1.5rem;
    border-bottom: 2px solid #007bff;
    padding-bottom: 0.5rem;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
    margin-bottom: 2rem;
}

.project-item {
    background-color: #2d3748;
    border-radius: 12px;
    overflow: hidden;
    border-left: 4px solid #007bff;
    color: #e2e8f0;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0, 123, 255, 0.2);
}

.project-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-bottom: 1px solid #4a5568;
}

.project-content {
    padding: 1.5rem;
}

.project-title {
    font-size: 1.3rem;
    font-weight: bold;
    color: #f7fafc;
    margin-bottom: 0.5rem;
}

.project-description {
    color: #cbd5e0;
    line-height: 1.6;
    margin-bottom: 1rem;
    font-size: 0.95rem;
}

.project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1rem;
}

.tech-tag {
    background-color: #007bff;
    color: white;
    padding: 0.25rem 0.75rem;
    border-radius: 15px;
    font-size: 0.8rem;
    font-weight: 500;
}

.project-links {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
}

.project-link {
    color: #63b3ed;
    text-decoration: none;
    font-weight: 600;
    font-size: 0.9rem;
    transition: color 0.2s ease;
}

.project-link:hover {
    color: #007bff;
    text-decoration: underline;
}

@media (max-width: 768px) {
    .projects-grid {
        grid-template-columns: 1fr;
        gap: 1.5rem;
    }
    
    .project-content {
        padding: 1rem;
    }
    
    .project-title {
        font-size: 1.2rem;
    }
}
</style>

# Featured Projects

<div class="projects-section">
    <div class="projects-grid">
        
        <div class="project-item">
            <img src="/assets/projects/youtube-logo.png" alt="YouTube Data Analysis" class="project-image">
            <div class="project-content">
                <div class="project-title">YouTube Data Analysis Dashboard</div>
                <div class="project-description">
                    Comprehensive analysis of YouTube trending videos data, featuring interactive visualizations and insights into video performance metrics, viewership patterns, and content trends across different categories and regions.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Pandas</span>
                    <span class="tech-tag">Matplotlib</span>
                    <span class="tech-tag">Seaborn</span>
                    <span class="tech-tag">Jupyter</span>
                </div>
                <div class="project-links">
                    <a href="https://github.com/AbdelrahmanEmad253/YouTube-Data-Analysis" class="project-link" target="_blank">View Code</a>
                    <a href="#" class="project-link">Live Demo</a>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/Leaf_Disease.jpg" alt="Leaf Disease Detection" class="project-image">
            <div class="project-content">
                <div class="project-title">Leaf Disease Detection System</div>
                <div class="project-description">
                    AI-powered plant disease detection system using computer vision and deep learning. Analyzes leaf images to identify diseases and provides treatment recommendations for agricultural applications.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">TensorFlow</span>
                    <span class="tech-tag">OpenCV</span>
                    <span class="tech-tag">CNN</span>
                    <span class="tech-tag">Computer Vision</span>
                </div>
                <div class="project-links">
                    <a href="https://github.com/AbdelrahmanEmad253/Leaf-Disease-Detection" class="project-link" target="_blank">View Code</a>
                    <a href="#" class="project-link">Live Demo</a>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/tech_market.png" alt="Tech Market Dashboard" class="project-image">
            <div class="project-content">
                <div class="project-title">Tech Market Analytics Dashboard</div>
                <div class="project-description">
                    Interactive dashboard for analyzing technology market trends, featuring real-time data visualization, market insights, and comprehensive analytics for tech industry stakeholders and investors.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Power BI</span>
                    <span class="tech-tag">SQL</span>
                    <span class="tech-tag">Data Visualization</span>
                    <span class="tech-tag">Business Intelligence</span>
                    <span class="tech-tag">Dashboard</span>
                </div>
                <div class="project-links">
                    <a href="https://github.com/AbdelrahmanEmad253/Tech-Market-Analytics" class="project-link" target="_blank">View Code</a>
                    <a href="#" class="project-link">Live Demo</a>
                </div>
            </div>
        </div>

    </div>
</div>

<div class="projects-section">
    <div class="projects-title">🌍 Additional Project Visualizations</div>
    
    <div class="projects-grid">
        <div class="project-item">
            <img src="/assets/projects/usa.jpg" alt="USA Data Visualization" class="project-image">
            <div class="project-content">
                <div class="project-title">USA Data Analysis</div>
                <div class="project-description">
                    Geographic data visualization and analysis of United States datasets, featuring interactive maps and regional insights.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Geopandas</span>
                    <span class="tech-tag">Plotly</span>
                    <span class="tech-tag">Data Visualization</span>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/egy1.jpg" alt="Egypt Data Visualization 1" class="project-image">
            <div class="project-content">
                <div class="project-title">Egypt Regional Analysis</div>
                <div class="project-description">
                    Comprehensive analysis of Egyptian regional data with interactive visualizations and demographic insights.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Matplotlib</span>
                    <span class="tech-tag">Seaborn</span>
                    <span class="tech-tag">Data Analysis</span>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/egy2.jpg" alt="Egypt Data Visualization 2" class="project-image">
            <div class="project-content">
                <div class="project-title">Egypt Economic Dashboard</div>
                <div class="project-description">
                    Economic indicators and trends analysis for Egypt with interactive charts and statistical insights.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Power BI</span>
                    <span class="tech-tag">Excel</span>
                    <span class="tech-tag">Statistical Analysis</span>
                    <span class="tech-tag">Dashboard</span>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/glob.jpg" alt="Global Data Visualization" class="project-image">
            <div class="project-content">
                <div class="project-title">Global Analytics Platform</div>
                <div class="project-description">
                    Worldwide data analysis platform featuring cross-country comparisons and global trend visualizations.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Tableau</span>
                    <span class="tech-tag">SQL</span>
                    <span class="tech-tag">Global Analytics</span>
                </div>
            </div>
        </div>

    </div>
</div> 