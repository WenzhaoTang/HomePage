---
layout: homepage
---

## About Me
I'm currently a <a href="https://www.tum.de/studium/studienangebot/detail/robotics-cognition-intelligence-master-of-science-msc" target="_blank"> Robotics, Cognition and Intelligence</a> master student at <a href="https://www.tum.de" target="_blank"> Technical University of Munich</a>'s <a href="https://www.cit.tum.de/cit/startseite/" target="_blank"> School of CIT</a>. I obtained my bachelor degree in Electronic Science and Technology from <a href="https://en.xidian.edu.cn" target="_blank"> Xidian University</a>.



## Research Interests
- **Artificial Intelligence:** 
- **Machine Learning:** 
- **Computer Vision:** 
- **Robot Perception:** 

## Projects

### Unsupervised 3D Reconstruction From Monocular Videos
<div>
    <!-- Always visible part -->
    We tried to improve a learning-based framework named NeuralRecon for real-time dense 3D geometry reconstruction from monocular video. For the supervised learning phase, the model is optimized by differentiating the weights of input features by leveraging the transformer or single attention layer.

    <!-- Toggle button -->
    <button onclick="toggleDescription('projectDescription')" style="cursor: pointer;">Show/Hide More</button>

    <!-- Collapsible part -->
    <div id="projectDescription" style="display: none;">
        Meanwhile, we calculate the supervised learning depth loss in the original NeuralRecon's loss calculation method and implement it by utilizing a differentiable renderer. For the test time, we introduce a robust photometric consistency loss to optimize the model for better results. Experiments on ScanNet demonstrate improved results compared to NeuralRecon. Further by replacing the training loss with the unsupervised robust photometric consistency loss, unsupervised learning-based 3D reconstruction is possible.
    </div>
</div>
[Code](https://github.com/WenzhaoTang/online_fusion) | [Pipeline](./assets/img/unsup_recon.png)
<!-- JavaScript function -->
<script>
    function toggleDescription(elementId) {
        var x = document.getElementById(elementId);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

### Automatic 3D Registration with Invisible Textures
<div>
    <!-- Always visible part -->
    Aiming to identify point correspondences of rigid 3D objects to a canonical model, particularly for monochromatic or low-texture objects, we enhanced correspondence detection through the application of artificial textures and a layer of fluorescent paint, preserving the object's original texture. 

    <!-- Toggle button -->
    <button onclick="toggleDescription('projectDescription')" style="cursor: pointer;">Show/Hide More</button>

    <!-- Collapsible part -->
    <div id="projectDescription" style="display: none;">
        Faced with the limitations of existing datasets, we introduced synthetic datasets to train robust models and evaluated classical template-matching techniques. Concurrently, we investigated various neural network architectures, assessing their performance on the TLESS-Dataset using the Surfemb method. After finalizing the dataset format, we created datasets featuring both non-textured and textured objects and commenced training. We then assessed the models' applicability and accuracy through both qualitative and quantitative evaluations. Moving forward, we plan to refine our models, leveraging ongoing feedback and considering the integration of more advanced architectures to achieve our goals.
    </div>
</div>
[Code](https://github.com/WenzhaoTang/3D-Registration) | [Synthetic Dataset](./assets/img/3Dreg.JPG)
<!-- JavaScript function -->
<script>
    function toggleDescription(elementId) {
        var x = document.getElementById(elementId);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

## Scholarships and Awards
- **Study Abroad Scholarship,** China Scholarship Council, 2019
- **First-class Scholarship,** Xidian University, 2018
- **Merit Student of** Xidian University, 2018


## Photographs
tbd

## Musics
I have a deep passion for music and have even set up my own cozy music studio. This is where I indulge in singing and mix my own tracks. Dive in to explore my musical journey at <a href="https://music.163.com/#/artist?id=34592658" target="_blank"> NetEase Cloud Music</a>!

<div style="display: flex; justify-content: space-between;">
    <a href="https://music.163.com/#/album?id=89273619" target="_blank">
        <img src="./assets/img/album-1.jpeg" alt="Album 1" style="width: 175px; margin-right: 20px; border: 2px solid white;">
    </a>
    <a href="https://music.163.com/#/album?id=132146650" target="_blank">
        <img src="./assets/img/album-2.jpeg" alt="Album 2" style="width: 175px; margin-right: 20px; border: 2px solid white;">
    </a>
    <a href="https://music.163.com/#/album?id=152251596" target="_blank">
        <img src="./assets/img/album-3.jpeg" alt="Album 3" style="width: 175px; border: 2px solid white;">
    </a>
</div>


## Misc.
<ul>
  <li>During my undergrad, I earned a spot among the Campus Top Ten Singers. This experience not only expanded my musical horizons but also introduced me to many talented peers.</li> 
  <li>I passionately support balanced feminist ideals, aim to promote diversity and equality, and believe in valuing everyone's unique contributions regardless of gender.</li>
</ul>
