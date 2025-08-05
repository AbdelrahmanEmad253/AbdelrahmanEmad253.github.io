---
icon: fas fa-code
order: 4
---

<style>
.skills-section {
    margin-bottom: 3rem;
}

.skills-title {
    font-size: 1.5rem;
    font-weight: bold;
    color: #007bff;
    margin-bottom: 1.5rem;
    border-bottom: 2px solid #007bff;
    padding-bottom: 0.5rem;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-bottom: 2rem;
}

.skill-item {
    background-color: #2d3748;
    border-radius: 8px;
    padding: 1.5rem;
    border-left: 4px solid #007bff;
    color: #e2e8f0;
    transition: transform 0.2s ease;
}

.skill-item:hover {
    transform: translateY(-2px);
}

.skill-header {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
}

.skill-icon {
    width: 60px;
    height: 60px;
    object-fit: contain;
    margin-right: 1rem;
    border-radius: 8px;
    background-color: #1a202c;
    padding: 8px;
}

.skill-title {
    font-size: 1.2rem;
    font-weight: bold;
    color: #f7fafc;
    margin-bottom: 0.5rem;
}

.skill-description {
    color: #cbd5e0;
    line-height: 1.6;
    font-size: 0.95rem;
}

.skill-list {
    list-style: none;
    padding: 0;
    margin-top: 1rem;
}

.skill-list li {
    color: #a0aec0;
    margin: 0.3rem 0;
    padding-left: 1rem;
    position: relative;
}

.skill-list li:before {
    content: "▸";
    color: #007bff;
    position: absolute;
    left: 0;
}

@media (max-width: 768px) {
    .skills-grid {
        grid-template-columns: 1fr;
        gap: 1rem;
    }
    
    .skill-item {
        padding: 1rem;
    }
    
    .skill-icon {
        width: 50px;
        height: 50px;
    }
    
    .skill-title {
        font-size: 1.1rem;
    }
}
</style>

# Technical Skills

<div class="skills-section">
    <div class="skills-title">🖥️ Programming Languages</div>
    
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Programming_languages.png" alt="Programming Languages" class="skill-icon">
                <div>
                    <div class="skill-title">Programming Languages</div>
                </div>
            </div>
            <div class="skill-description">
                Advanced proficiency in multiple programming languages for data analysis, machine learning, and automation.
            </div>
            <ul class="skill-list">
                <li><strong>Python:</strong> Data analysis, machine learning, automation</li>
                <li><strong>SQL:</strong> Complex queries, database design, optimization</li>
                <li><strong>R:</strong> Statistical analysis and data visualization</li>
            </ul>
        </div>
    </div>
</div>

<div class="skills-section">
    <div class="skills-title">🤖 AI/ML Tools</div>
    
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Machine Learning & AI Tools.jpeg" alt="Machine Learning & AI Tools" class="skill-icon">
                <div>
                    <div class="skill-title">Machine Learning & AI</div>
                </div>
            </div>
            <div class="skill-description">
                Comprehensive expertise in machine learning frameworks and AI development tools.
            </div>
            <ul class="skill-list">
                <li><strong>TensorFlow & Keras:</strong> Deep learning models and neural networks</li>
                <li><strong>Scikit-learn:</strong> Machine learning algorithms and model development</li>
                <li><strong>SpaCy & NLTK:</strong> Natural language processing and text analysis</li>
            </ul>
        </div>

        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Deep Learning.png" alt="Deep Learning" class="skill-icon">
                <div>
                    <div class="skill-title">Deep Learning</div>
                </div>
            </div>
            <div class="skill-description">
                Specialized knowledge in deep learning architectures and neural network development.
            </div>
            <ul class="skill-list">
                <li><strong>Neural Networks:</strong> CNN, RNN, LSTM architectures</li>
                <li><strong>Computer Vision:</strong> Image recognition and processing</li>
                <li><strong>Natural Language Processing:</strong> Text analysis and generation</li>
            </ul>
        </div>
    </div>
</div>

<div class="skills-section">
    <div class="skills-title">📊 Data Analysis & Visualization</div>
    
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Data Analysis & Tools.png" alt="Data Analysis & Tools" class="skill-icon">
                <div>
                    <div class="skill-title">Data Analysis Tools</div>
                </div>
            </div>
            <div class="skill-description">
                Advanced tools for data manipulation, analysis, and statistical computing.
            </div>
            <ul class="skill-list">
                <li><strong>Pandas & NumPy:</strong> Data manipulation and numerical computing</li>
                <li><strong>Power Query:</strong> ETL processes and data transformation</li>
                <li><strong>Excel:</strong> Advanced analytics and modeling</li>
            </ul>
        </div>

        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Data Visualization Tools.png" alt="Data Visualization Tools" class="skill-icon">
                <div>
                    <div class="skill-title">Visualization & BI</div>
                </div>
            </div>
            <div class="skill-description">
                Professional tools for creating interactive dashboards and business intelligence solutions.
            </div>
            <ul class="skill-list">
                <li><strong>Power BI:</strong> Interactive dashboards and business intelligence</li>
                <li><strong>Tableau:</strong> Data visualization and analytics</li>
                <li><strong>Looker Studio:</strong> Custom reporting and data exploration</li>
            </ul>
        </div>
    </div>
</div>

<div class="skills-section">
    <div class="skills-title">🗄️ Database Management</div>
    
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-header">
                <img src="/assets/icons/Database Management.png" alt="Database Management" class="skill-icon">
                <div>
                    <div class="skill-title">Database Systems</div>
                </div>
            </div>
            <div class="skill-description">
                Expertise in database design, management, and optimization across multiple platforms.
            </div>
            <ul class="skill-list">
                <li><strong>SQL Server:</strong> Database management and optimization</li>
                <li><strong>MongoDB:</strong> NoSQL database operations</li>
                <li><strong>Firebase:</strong> Real-time database and cloud services</li>
            </ul>
        </div>
    </div>
</div> 