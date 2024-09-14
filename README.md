## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Engineer - GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Header section */
        header {
            background-color: #007acc;
            color: #fff;
            padding: 40px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        header img {
            position: absolute;
            top: 50%;
            left: -100px;
            width: 150px;
            height: 150px;
            transform: translateY(-50%);
            animation: slideIn 4s infinite alternate;
        }

        header h1 {
            animation: fadeInDown 2s ease;
        }

        header p {
            animation: fadeInUp 2s ease;
        }

        @keyframes fadeInDown {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            0% { left: -150px; }
            100% { left: 50px; }
        }

        /* General layout */
        section {
            margin: 20px;
            animation: fadeIn 1.5s ease;
        }

        h1, h2 {
            color: #007acc;
        }

        .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }

    .skills span {
        background-color: #007acc;
        color: #fff;
        padding: 8px 12px;
        border-radius: 5px;
        font-size: 14px;
        opacity: 0;  /* Initially hidden */
        transform: translateY(20px); /* Move down initially */
        animation: fadeInSkills 1s ease forwards; /* Fade-in animation */
    }

    /* Keyframes for fade-in and slide-up effect */
    @keyframes fadeInSkills {
        to {
            opacity: 1; /* Fully visible */
            transform: translateY(0); /* Slide-up to original position */
        }
    }

    /* Stagger the animation for each skill */
    .skills span:nth-child(1) {
        animation-delay: 0.2s;
    }

    .skills span:nth-child(2) {
        animation-delay: 0.4s;
    }

    .skills span:nth-child(3) {
        animation-delay: 0.6s;
    }

    .skills span:nth-child(4) {
        animation-delay: 0.8s;
    }

    .skills span:nth-child(5) {
        animation-delay: 1s;
    }

    .skills span:nth-child(6) {
        animation-delay: 1.2s;
    }

    .skills span:nth-child(7) {
        animation-delay: 1.4s;
    }

    .skills span:nth-child(8) {
        animation-delay: 1.6s;
    }

    .skills span:nth-child(9) {
        animation-delay: 1.8s;
    }

    .skills span:nth-child(10) {
        animation-delay: 2s;
    }

    .skills span:nth-child(11) {
        animation-delay: 2.2s;
    }

    .skills span:nth-child(12) {
        animation-delay: 2.4s;
    }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #007acc;
            color: #fff;
        }

        a {
            color: #007acc;
            text-decoration: none;
        }

        img.project {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>

<header>
    <img src="your-photo-url-here" alt="Profile Photo">
    <h1>👋 Hi, I'm Omar Badawi!</h1>
    <p>AI Engineer | Deep Learning | Computer Vision | Neural Networks | Python & C++</p>
</header>

<section>
    <h2>🧠 About Me</h2>
    <p>🔭 I’m currently working on projects involving <strong>Nvidia Jetson</strong> and <strong>TensorFlow</strong>.</p>
    <p>🌱 I’m constantly learning more about <strong>neural networks</strong>, <strong>AI deployment</strong>, and <strong>image processing</strong>.</p>
    <p>💬 Ask me about <strong>Python</strong>, <strong>C++</strong>, <strong>deep learning</strong>, and <strong>computer vision</strong>.</p>
    <p>📫 How to reach me: <a href="mailto:omarmagdybadawi@gmail.com">omarmagdybadawi@gmail.com</a> or connect with me on <a href="https://www.linkedin.com/in/omar-badawi-9181b1243?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a>.</p>
</section>

<section>
    <h2>🛠 Technologies & Tools</h2>
    <div class="skills">
        <span>Python</span>
        <span>C++</span>
        <span>TensorFlow</span>
        <span>Keras</span>
        <span>OpenCV</span>
        <span>scikit-image</span>
        <span>Nvidia Jetson</span>
        <span>Html</span>
        <span>Css</span>
        <span>Git</span>
        <span>GitHub</span>

    </div>
</section>
<!--
<section>
    <h2>🚀 Projects</h2>

    <h3><a href="https://github.com/your-profile/ai-powered-image-classifier" target="_blank">Project 1: AI-Powered Image Classifier</a></h3>
    <img src="your-project-image1-url-here" alt="Project Image 1" class="project">
    <p>Built a deep learning model using <strong>TensorFlow</strong> to classify images with 95% accuracy. Deployed on <strong>Nvidia Jetson</strong> for real-time image recognition.</p>

    <h3><a href="https://github.com/your-profile/predictive-analysis-nn" target="_blank">Project 2: Neural Network for Predictive Analysis</a></h3>
    <img src="your-project-image2-url-here" alt="Project Image 2" class="project">
    <p>Developed a custom neural network using <strong>Keras</strong> for time-series data prediction. Implemented custom loss functions and achieved state-of-the-art results.</p>
</section>
-->
<section>
    <h2>📊 GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=OmarBadawi&show_icons=true&theme=radical" alt="GitHub Stats">
</section>

<footer>
    <p>🌍 Connect with Me: <a href="https://www.linkedin.com/in/omar-badawi-9181b1243?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a>
</footer>

</body>
</html>
