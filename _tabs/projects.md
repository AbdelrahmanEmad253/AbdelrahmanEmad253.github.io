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
    padding: 0.5rem 1rem;
    border: 1px solid #63b3ed;
    border-radius: 5px;
}

.project-link:hover {
    color: #007bff;
    background-color: #007bff;
    color: white;
}

.dashboard-button {
    background-color: #28a745;
    color: white;
    text-decoration: none;
    font-weight: 600;
    font-size: 0.9rem;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    transition: background-color 0.2s ease;
    display: inline-block;
    margin-top: 0.5rem;
    cursor: pointer;
    border: none;
}

.dashboard-button:hover {
    background-color: #218838;
    color: white;
}

/* Dashboard Modal Styles */
.dashboard-modal {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8);
    overflow-y: auto;
}

.dashboard-modal-content {
    background-color: #1a202c;
    margin: 5% auto;
    padding: 2rem;
    border-radius: 12px;
    width: 90%;
    max-width: 1200px;
    position: relative;
    color: #e2e8f0;
}

.close-modal {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
    cursor: pointer;
    position: absolute;
    right: 1rem;
    top: 1rem;
}

.close-modal:hover {
    color: #fff;
}

.dashboard-images {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    margin-top: 2rem;
}

.dashboard-image-container {
    text-align: center;
}

.dashboard-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.dashboard-image-title {
    font-size: 1.2rem;
    font-weight: bold;
    color: #f7fafc;
    margin-bottom: 1rem;
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
    
    .dashboard-modal-content {
        width: 95%;
        margin: 2% auto;
        padding: 1rem;
    }
}
</style>

# Featured Projects

<div class="projects-section">
    <div class="projects-grid">
        
        <div class="project-item">
            <img src="/assets/projects/youtube-logo.png" alt="YouTube Data Analysis" class="project-image">
            <div class="project-content">
                <div class="project-title">YouTube Transcript Analysis</div>
                <div class="project-description">
                    AI-powered YouTube transcript analysis system developed during the Mentorness AI internship. Features natural language processing to extract insights from video transcripts and analyze content patterns.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">NLP</span>
                    <span class="tech-tag">YouTube API</span>
                    <span class="tech-tag">Text Analysis</span>
                    <span class="tech-tag">AI</span>
                </div>
                <div class="project-links">
                    <a href="https://github.com/AbdelrahmanEmad253/youtube_transcript.git" class="project-link" target="_blank">View Code</a>
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
                    <a href="https://github.com/AbdelrahmanEmad253/LEAF_DISEASE_DETECTION" class="project-link" target="_blank">View Code</a>
                </div>
            </div>
        </div>

        <div class="project-item">
            <img src="/assets/projects/tech_market.png" alt="Tech Market Dashboard" class="project-image">
            <div class="project-content">
                <div class="project-title">Tech Market Analytics Dashboard</div>
                <div class="project-description">
                    Comprehensive analysis of over 600,000 tech job listings from 7 major platforms including TechLayoff, Upwork, Indeed, Wuzzuf, Egytech, Monster, and RemoteOK. Features interactive Power BI dashboards with job market insights, salary analysis, and trend visualizations.
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Power BI</span>
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Web Scraping</span>
                    <span class="tech-tag">Data Analysis</span>
                    <span class="tech-tag">Jupyter</span>
                </div>
                <div class="project-links">
                    <a href="https://github.com/AbdelrahmanEmad253/TechMarket_Analysis.git" class="project-link" target="_blank">View Code</a>
                    <a href="https://app.powerbi.com/groups/me/reports/9aca18a9-c0fd-4cc7-b92c-e3af25552905/4f0343399a198c4984b9?experience=power-bi" class="dashboard-button" target="_blank">View Interactive Dashboard</a>
                </div>
            </div>
        </div>

    </div>
</div> 