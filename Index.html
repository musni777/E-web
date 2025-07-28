document.addEventListener('DOMContentLoaded', function() {
    // Form elements
    const form = document.getElementById('portfolio-form');
    const steps = document.querySelectorAll('.form-step');
    const nextButtons = document.querySelectorAll('.next-btn');
    const prevButtons = document.querySelectorAll('.prev-btn');
    const progressBar = document.getElementById('progress-bar');
    const progressSteps = document.querySelectorAll('.step');
    const previewBtn = document.getElementById('preview-btn');
    const downloadBtn = document.getElementById('download-btn');
    const regenerateBtn = document.getElementById('regenerate-btn');
    const closeBtn = document.querySelector('.close-btn');
    const previewModal = document.getElementById('preview-modal');
    const previewContainer = document.getElementById('preview-container');
    
    // Experience
    const experienceContainer = document.getElementById('experience-container');
    const addExperienceBtn = document.querySelector('.add-experience-btn');
    
    // Education
    const educationContainer = document.getElementById('education-container');
    const addEducationBtn = document.querySelector('.add-education-btn');
    
    // Projects
    const projectsContainer = document.getElementById('projects-container');
    const addProjectBtn = document.querySelector('.add-project-btn');
    
    // Image upload
    const profilePicInput = document.getElementById('profile-pic');
    const profileUpload = document.getElementById('profile-upload');
    const imagePreview = document.getElementById('image-preview');
    
    // Design options
    const themeSelect = document.getElementById('theme');
    const customColors = document.getElementById('custom-colors');
    const primaryColor = document.getElementById('primary-color');
    const secondaryColor = document.getElementById('secondary-color');
    const backgroundColor = document.getElementById('background-color');
    const textColor = document.getElementById('text-color');
    const layoutSelect = document.getElementById('layout');
    const fontSelect = document.getElementById('font');
    
    let currentStep = 1;
    let experienceCount = 1;
    let educationCount = 1;
    let projectCount = 1;
    
    // Initialize form
    showStep(currentStep);
    
    // Next button click handler
    nextButtons.forEach(button => {
        button.addEventListener('click', () => {
            if (validateStep(currentStep)) {
                currentStep++;
                showStep(currentStep);
                updateProgressBar();
            }
        });
    });
    
    // Previous button click handler
    prevButtons.forEach(button => {
        button.addEventListener('click', () => {
            currentStep--;
            showStep(currentStep);
            updateProgressBar();
        });
    });
    
    // Show current step
    function showStep(step) {
        steps.forEach(formStep => {
            formStep.classList.remove('active');
            if (parseInt(formStep.dataset.step) === step) {
                formStep.classList.add('active');
            }
        });
        
        progressSteps.forEach((progressStep, index) => {
            if (index < step) {
                progressStep.classList.add('active');
            } else {
                progressStep.classList.remove('active');
            }
        });
    }
    
    // Validate current step before proceeding
    function validateStep(step) {
        let isValid = true;
        const currentFormStep = document.querySelector(`.form-step[data-step="${step}"]`);
        
        // Check all required fields in current step
        const inputs = currentFormStep.querySelectorAll('input[required], textarea[required], select[required]');
        inputs.forEach(input => {
            if (!input.value.trim()) {
                input.style.borderColor = 'red';
                isValid = false;
                
                // Reset border color when user starts typing
                input.addEventListener('input', () => {
                    input.style.borderColor = '';
                });
            }
        });
        
        return isValid;
    }
    
    // Update progress bar
    function updateProgressBar() {
        const progressPercentage = (currentStep / steps.length) * 100;
        progressBar.style.width = `${progressPercentage}%`;
    }
    
    // Add experience field
    addExperienceBtn.addEventListener('click', () => {
        experienceCount++;
        const newExperience = document.createElement('div');
        newExperience.className = 'experience-item';
        newExperience.innerHTML = `
            <div class="form-group">
                <label for="job-title-${experienceCount}">Job Title</label>
                <input type="text" id="job-title-${experienceCount}" class="job-title" required>
            </div>
            <div class="form-group">
                <label for="company-${experienceCount}">Company</label>
                <input type="text" id="company-${experienceCount}" class="company" required>
            </div>
            <div class="form-group">
                <label for="duration-${experienceCount}">Duration</label>
                <input type="text" id="duration-${experienceCount}" class="duration" placeholder="e.g. Jan 2020 - Present" required>
            </div>
            <div class="form-group">
                <label for="description-${experienceCount}">Description</label>
                <textarea id="description-${experienceCount}" class="description" rows="3" required></textarea>
            </div>
            <button type="button" class="remove-btn">×</button>
        `;
        experienceContainer.appendChild(newExperience);
        
        // Add event listener to remove button
        newExperience.querySelector('.remove-btn').addEventListener('click', () => {
            experienceContainer.removeChild(newExperience);
        });
    });
    
    // Add education field
    addEducationBtn.addEventListener('click', () => {
        educationCount++;
        const newEducation = document.createElement('div');
        newEducation.className = 'education-item';
        newEducation.innerHTML = `
            <div class="form-group">
                <label for="degree-${educationCount}">Degree/Certificate</label>
                <input type="text" id="degree-${educationCount}" class="degree" required>
            </div>
            <div class="form-group">
                <label for="institution-${educationCount}">Institution</label>
                <input type="text" id="institution-${educationCount}" class="institution" required>
            </div>
            <div class="form-group">
                <label for="year-${educationCount}">Year</label>
                <input type="text" id="year-${educationCount}" class="year" placeholder="e.g. 2015-2019" required>
            </div>
            <button type="button" class="remove-btn">×</button>
        `;
        educationContainer.appendChild(newEducation);
        
        // Add event listener to remove button
        newEducation.querySelector('.remove-btn').addEventListener('click', () => {
            educationContainer.removeChild(newEducation);
        });
    });
    
    // Add project field
    addProjectBtn.addEventListener('click', () => {
        projectCount++;
        const newProject = document.createElement('div');
        newProject.className = 'project-item';
        newProject.innerHTML = `
            <div class="form-group">
                <label for="project-title-${projectCount}">Project Title</label>
                <input type="text" id="project-title-${projectCount}" class="project-title" required>
            </div>
            <div class="form-group">
                <label for="project-desc-${projectCount}">Description</label>
                <textarea id="project-desc-${projectCount}" class="project-desc" rows="3" required></textarea>
            </div>
            <div class="form-group">
                <label for="project-link-${projectCount}">Link (optional)</label>
                <input type="url" id="project-link-${projectCount}" class="project-link">
            </div>
            <button type="button" class="remove-btn">×</button>
        `;
        projectsContainer.appendChild(newProject);
        
        // Add event listener to remove button
        newProject.querySelector('.remove-btn').addEventListener('click', () => {
            projectsContainer.removeChild(newProject);
        });
    });
    
    // Handle image upload
    profileUpload.addEventListener('change', function(e) {
        const file = e.target.files[0];
        if (file) {
            const reader = new FileReader();
            reader.onload = function(event) {
                imagePreview.innerHTML = `<img src="${event.target.result}" alt="Profile Preview">`;
                imagePreview.style.display = 'block';
                profilePicInput.value = event.target.result; // Set the URL input to data URL
            };
            reader.readAsDataURL(file);
        }
    });
    
    // Handle URL input for profile picture
    profilePicInput.addEventListener('change', function() {
        if (this.value) {
            imagePreview.innerHTML = `<img src="${this.value}" alt="Profile Preview">`;
            imagePreview.style.display = 'block';
        } else {
            imagePreview.style.display = 'none';
        }
    });
    
    // Show/hide custom color options
    themeSelect.addEventListener('change', function() {
        if (this.value === 'custom') {
            customColors.style.display = 'block';
        } else {
            customColors.style.display = 'none';
        }
    });
    
    // Preview button click handler
    previewBtn.addEventListener('click', function() {
        if (validateStep(currentStep)) {
            generatePreview();
            previewModal.style.display = 'block';
        }
    });
    
    // Close modal
    closeBtn.addEventListener('click', function() {
        previewModal.style.display = 'none';
    });
    
    // Regenerate button click handler
    regenerateBtn.addEventListener('click', function() {
        generatePreview();
    });
    
    // Download button click handler
    downloadBtn.addEventListener('click', function() {
        downloadPortfolio();
    });
    
    // Close modal when clicking outside
    window.addEventListener('click', function(e) {
        if (e.target === previewModal) {
            previewModal.style.display = 'none';
        }
    });
    
    // Generate portfolio preview
    function generatePreview() {
        // Get all form data
        const formData = {
            basicInfo: {
                name: document.getElementById('name').value,
                profession: document.getElementById('profession').value,
                bio: document.getElementById('bio').value,
                profilePic: document.getElementById('profile-pic').value || 'https://via.placeholder.com/150'
            },
            experiences: [],
            education: [],
            skills: document.getElementById('skills').value.split(',').map(skill => skill.trim()),
            contact: {
                email: document.getElementById('email').value,
                phone: document.getElementById('phone').value,
                address: document.getElementById('address').value,
                linkedin: document.getElementById('linkedin').value,
                github: document.getElementById('github').value,
                website: document.getElementById('website').value
            },
            projects: [],
            design: {
                theme: themeSelect.value,
                primaryColor: primaryColor.value,
                secondaryColor: secondaryColor.value,
                backgroundColor: backgroundColor.value,
                textColor: textColor.value,
                layout: layoutSelect.value,
                font: fontSelect.value
            }
        };
        
        // Get experiences
        document.querySelectorAll('.experience-item').forEach(item => {
            formData.experiences.push({
                jobTitle: item.querySelector('.job-title').value,
                company: item.querySelector('.company').value,
                duration: item.querySelector('.duration').value,
                description: item.querySelector('.description').value
            });
        });
        
        // Get education
        document.querySelectorAll('.education-item').forEach(item => {
            formData.education.push({
                degree: item.querySelector('.degree').value,
                institution: item.querySelector('.institution').value,
                year: item.querySelector('.year').value
            });
        });
        
        // Get projects
        document.querySelectorAll('.project-item').forEach(item => {
            formData.projects.push({
                title: item.querySelector('.project-title').value,
                description: item.querySelector('.project-desc').value,
                link: item.querySelector('.project-link').value
            });
        });
        
        // Generate HTML for preview
        previewContainer.innerHTML = generatePortfolioHTML(formData);
    }
    
    // Generate portfolio HTML
    function generatePortfolioHTML(data) {
        let primaryColor = data.design.theme === 'custom' ? data.design.primaryColor : 
                          data.design.theme === 'dark' ? '#34495e' :
                          data.design.theme === 'blue' ? '#3498db' :
                          data.design.theme === 'green' ? '#27ae60' :
                          data.design.theme === 'purple' ? '#9b59b6' : '#3498db';
        
        let secondaryColor = data.design.theme === 'custom' ? data.design.secondaryColor : 
                            data.design.theme === 'dark' ? '#2c3e50' :
                            data.design.theme === 'blue' ? '#2980b9' :
                            data.design.theme === 'green' ? '#219653' :
                            data.design.theme === 'purple' ? '#8e44ad' : '#2c3e50';
        
        let backgroundColor = data.design.theme === 'custom' ? data.design.backgroundColor : 
                             data.design.theme === 'dark' ? '#1a1a1a' : '#f9f9f9';
        
        let textColor = data.design.theme === 'custom' ? data.design.textColor : 
                        data.design.theme === 'dark' ? '#ecf0f1' : '#333';
        
        let font = data.design.font;
        
        return `
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>${data.basicInfo.name} - Portfolio</title>
            <link href="https://fonts.googleapis.com/css2?family=${font.split("'")[1] || 'Open+Sans'}:wght@400;600;700&display=swap" rel="stylesheet">
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
            <style>
                :root {
                    --primary-color: ${primaryColor};
                    --secondary-color: ${secondaryColor};
                    --background-color: ${backgroundColor};
                    --text-color: ${textColor};
                    --light-gray: #f5f5f5;
                    --gray: #ddd;
                    --dark-gray: #777;
                }
                
                * {
                    margin: 0;
                    padding: 0;
                    box-sizing: border-box;
                }
                
                body {
                    font-family: ${font};
                    background-color: var(--background-color);
                    color: var(--text-color);
                    line-height: 1.6;
                }
                
                .portfolio-header {
                    text-align: center;
                    padding: 60px 20px;
                    background-color: var(--primary-color);
                    color: white;
                }
                
                .portfolio-header img {
                    width: 180px;
                    height: 180px;
                    border-radius: 50%;
                    object-fit: cover;
                    border: 5px solid white;
                    margin-bottom: 20px;
                }
                
                .portfolio-header h1 {
                    font-size: 2.8rem;
                    margin: 10px 0;
                }
                
                .portfolio-header p {
                    font-size: 1.3rem;
                    max-width: 800px;
                    margin: 0 auto;
                }
                
                .portfolio-section {
                    padding: 60px 20px;
                    max-width: 1200px;
                    margin: 0 auto;
                }
                
                .section-title {
                    color: var(--primary-color);
                    margin-bottom: 40px;
                    text-align: center;
                    font-size: 2.2rem;
                    position: relative;
                }
                
                .section-title::after {
                    content: '';
                    display: block;
                    width: 80px;
                    height: 4px;
                    background-color: var(--primary-color);
                    margin: 15px auto;
                }
                
                .about-section {
                    background-color: var(--background-color);
                }
                
                .about-content {
                    max-width: 800px;
                    margin: 0 auto;
                    text-align: center;
                    font-size: 1.1rem;
                }
                
                .experience-item-preview, .education-item-preview, .project-item-preview {
                    margin-bottom: 30px;
                    padding: 30px;
                    background-color: ${data.design.theme === 'dark' ? '#2c2c2c' : 'white'};
                    border-radius: 8px;
                    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                }
                
                .item-title {
                    font-size: 1.4rem;
                    color: var(--secondary-color);
                    margin-bottom: 8px;
                }
                
                .item-subtitle {
                    color: var(--text-color);
                    margin-bottom: 10px;
                    font-weight: 600;
                    font-size: 1.1rem;
                }
                
                .item-duration {
                    color: var(--dark-gray);
                    margin-bottom: 15px;
                    font-style: italic;
                }
                
                .skills-container {
                    display: flex;
                    flex-wrap: wrap;
                    gap: 15px;
                    justify-content: center;
                    margin-top: 20px;
                }
                
                .skill-tag {
                    background-color: var(--primary-color);
                    color: white;
                    padding: 8px 20px;
                    border-radius: 20px;
                    font-size: 1rem;
                }
                
                .contact-info {
                    display: flex;
                    flex-wrap: wrap;
                    justify-content: center;
                    gap: 30px;
                    margin-top: 30px;
                }
                
                .contact-item {
                    display: flex;
                    align-items: center;
                    gap: 10px;
                    font-size: 1.1rem;
                }
                
                .contact-item a {
                    color: var(--primary-color);
                    text-decoration: none;
                }
                
                .contact-item a:hover {
                    text-decoration: underline;
                }
                
                .portfolio-footer {
                    text-align: center;
                    padding: 30px;
                    background-color: var(--secondary-color);
                    color: white;
                }
                
                .projects-grid {
                    display: grid;
                    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
                    gap: 30px;
                    margin-top: 30px;
                }
                
                .project-link-btn {
                    display: inline-block;
                    margin-top: 15px;
                    padding: 8px 20px;
                    background-color: var(--primary-color);
                    color: white;
                    text-decoration: none;
                    border-radius: 5px;
                    transition: background-color 0.3s;
                }
                
                .project-link-btn:hover {
                    background-color: var(--secondary-color);
                }
                
                @media (max-width: 768px) {
                    .portfolio-header h1 {
                        font-size: 2rem;
                    }
                    
                    .portfolio-header p {
                        font-size: 1.1rem;
                    }
                    
                    .section-title {
                        font-size: 1.8rem;
                    }
                    
                    .contact-info {
                        flex-direction: column;
                        align-items: center;
                        gap: 15px;
                    }
                    
                    .projects-grid {
                        grid-template-columns: 1fr;
                    }
                }
            </style>
        </head>
        <body>
            <header class="portfolio-header">
                <img src="${data.basicInfo.profilePic}" alt="${data.basicInfo.name}">
                <h1>${data.basicInfo.name}</h1>
                <p>${data.basicInfo.profession}</p>
            </header>
            
            <section class="portfolio-section about-section">
                <h2 class="section-title">About Me</h2>
                <div class="about-content">
                    <p>${data.basicInfo.bio}</p>
                </div>
            </section>
            
            <section class="portfolio-section">
                <h2 class="section-title">Work Experience</h2>
                ${data.experiences.map(exp => `
                    <div class="experience-item-preview">
                        <h3 class="item-title">${exp.jobTitle}</h3>
                        <h4 class="item-subtitle">${exp.company}</h4>
                        <p class="item-duration">${exp.duration}</p>
                        <p>${exp.description}</p>
                    </div>
                `).join('')}
            </section>
            
            <section class="portfolio-section">
                <h2 class="section-title">Education</h2>
                ${data.education.map(edu => `
                    <div class="education-item-preview">
                        <h3 class="item-title">${edu.degree}</h3>
                        <h4 class="item-subtitle">${edu.institution}</h4>
                        <p class="item-duration">${edu.year}</p>
                    </div>
                `).join('')}
            </section>
            
            <section class="portfolio-section">
                <h2 class="section-title">Skills</h2>
                <div class="skills-container">
                    ${data.skills.map(skill => `
                        <div class="skill-tag">${skill}</div>
                    `).join('')}
                </div>
            </section>
            
            <section class="portfolio-section">
                <h2 class="section-title">Projects</h2>
                <div class="projects-grid">
                    ${data.projects.map(project => `
                        <div class="project-item-preview">
                            <h3 class="item-title">${project.title}</h3>
                            <p>${project.description}</p>
                            ${project.link ? `<a href="${project.link}" class="project-link-btn" target="_blank">View Project</a>` : ''}
                        </div>
                    `).join('')}
                </div>
            </section>
            
            <section class="portfolio-section">
                <h2 class="section-title">Contact</h2>
                <div class="contact-info">
                    ${data.contact.email ? `<div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <a href="mailto:${data.contact.email}">${data.contact.email}</a>
                    </div>` : ''}
                    
                    ${data.contact.phone ? `<div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <span>${data.contact.phone}</span>
                    </div>` : ''}
                    
                    ${data.contact.address ? `<div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>${data.contact.address}</span>
                    </div>` : ''}
                    
                    ${data.contact.linkedin ? `<div class="contact-item">
                        <i class="fab fa-linkedin"></i>
                        <a href="${data.contact.linkedin}" target="_blank">LinkedIn</a>
                    </div>` : ''}
                    
                    ${data.contact.github ? `<div class="contact-item">
                        <i class="fab fa-github"></i>
                        <a href="${data.contact.github}" target="_blank">GitHub</a>
                    </div>` : ''}
                    
                    ${data.contact.website ? `<div class="contact-item">
                        <i class="fas fa-globe"></i>
                        <a href="${data.contact.website}" target="_blank">Website</a>
                    </div>` : ''}
                </div>
            </section>
            
            <footer class="portfolio-footer">
                <p>&copy; ${new Date().getFullYear()} ${data.basicInfo.name}. All rights reserved.</p>
            </footer>
        </body>
        </html>
        `;
    }
    
    // Download portfolio as ZIP file
    function downloadPortfolio() {
        // Get the generated HTML
        const htmlContent = previewContainer.innerHTML;
        
        // Create a blob with the HTML content
        const htmlBlob = new Blob([htmlContent], { type: 'text/html' });
        
        // Create a blob with a basic CSS file (could be enhanced)
        const cssContent = `
        /* Additional CSS for the portfolio */
        body {
            font-family: ${document.getElementById('font').value};
            line-height: 1.6;
            color: ${textColor.value};
            background-color: ${backgroundColor.value};
        }
        
        a {
            color: ${primaryColor.value};
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        `;
        
        const cssBlob = new Blob([cssContent], { type: 'text/css' });
        
        // Create a ZIP file using JSZip
        const zip = new JSZip();
        zip.file("index.html", htmlContent);
        zip.file("styles.css", cssContent);
        
        // Add profile image if it's a data URL
        const profilePic = document.getElementById('profile-pic').value;
        if (profilePic.startsWith('data:image')) {
            const base64Data = profilePic.split(',')[1];
            zip.file("profile.jpg", base64Data, { base64: true });
        }
        
        // Generate the ZIP file
        zip.generateAsync({ type: "blob" }).then(function(content) {
            // Create download link
            const a = document.createElement('a');
            const url = URL.createObjectURL(content);
            a.href = url;
            a.download = 'portfolio.zip';
            document.body.appendChild(a);
            a.click();
            
            // Clean up
            setTimeout(function() {
                document.body.removeChild(a);
                URL.revokeObjectURL(url);
            }, 0);
        });
    }
    
    // Load JSZip library dynamically
    function loadJSZip() {
        return new Promise((resolve, reject) => {
            if (typeof JSZip !== 'undefined') {
                resolve();
                return;
            }
            
            const script = document.createElement('script');
            script.src = 'https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js';
            script.onload = resolve;
            script.onerror = reject;
            document.head.appendChild(script);
        });
    }
    
    // Initialize JSZip when download button is first clicked
    downloadBtn.addEventListener('click', function initJSZip() {
        loadJSZip().catch(error => {
            alert('Failed to load ZIP library. Please try again.');
            console.error(error);
        });
        downloadBtn.removeEventListener('click', initJSZip);
    }, { once: true });
});
