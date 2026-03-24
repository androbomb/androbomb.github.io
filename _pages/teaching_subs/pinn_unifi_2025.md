<!--
List of icons for lectures
empty box  : <i class="far fa-square"> 
spin icon  : <i class="fas fa-atom fa-spin"></i>
checked box: <i class="far fa--checksquare">
-->

<div class="card mt-3">
  <div class="p-3">
    <div class="row">
      <div class="col-sm-10">
        <h5 class="font-weight-bold">Numerical resolution of Differential Equations for applications using Physics-Informed Neural Networks (A.A. 2024/25)</h5>
      </div>
      <div class="col-sm-2 text-left text-sm-right">
        <span class="badge font-weight-bold danger-color-dark align-middle">
            4CFU (16hrs) [SC]
        </span>
        <span class="badge font-weight-bold danger-color align-middle">
            3CFU (18hrs) [Ph]
        </span>
      </div>
    </div>
    <h6 class="font-italic mt-2 mt-sm-0">Winter 2025: Lecturer</h6>
    <ul class="card-text font-weight-light list-group list-group-flush"  style="background-color: var(--global-card-bg-color); color: var(--global-text-color);">
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
        Graduate-level introduction to PINNs. <a href="https://docs.google.com/document/d/1zYZ4OYqSOOiPHbiOz0AlpJRBDfapbNXXSNP9ntWiBI8/edit?usp=sharing">Syllabus</a>. 
        <p>All interested students should contact me at my <a href="mailto:bombini@fi.infn.it">personal mail</a>.  <b><i>Elegible also as a course for the PhD in Physics.</i></b> </p>
        <!-- summary -->
        <p><b>Summary</b>: </p>
        <p><i>The goal of the course is to introduce the concept of Physics Informed Deep Neural Networks (PINN), discuss its implementation from scratch in PyTorch and using advanced ad-hoc developed open-source libraries such as nvidia-modulus for addressing real-world problems in various fields (engineering, physics, petroleum reservoir). We discuss recent topics such as Mixture-of-Models, Neural Operators, Physics-Informed Kolmogorov-Arnold Networks and Physics-Informed Computer Vision.</i> </p>
        <p><b>Exam</b>:</p>
        <p>Option a: <i>Discussion of a research work on the topic, selected by the student and accepted by the instructor; it has to be presented orally with a presentation and with a Git repo offering the students implementation of the code. </i></p>
        <p>Option b<i>: Resolution of a small research problem discussed jointly with the instructor; presented either orally with a brief presentation or a written essay, and a Git repo.</i></p>
        <b>Repository with notebooks and other utilities:</b> <a href="https://pandora.infn.it/public/pinn-smart-computing-utils">pandora.infn.it</a> (it is password protected; I'll give it during the course)
      </li>
      <!-- Lectures -->
      <!-- 1 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <b>0. General Introduction to the course: Motivation, Recaps of Mathematical Analysis, Functional Analysis, Montecarlo Integration </b> (1h+1h): <a href="https://docs.google.com/presentation/d/1ZpQ0z5tdmq7_ukqvaUT_M6TnTJXDVAurUA9cDJKWJzA/edit?usp=sharing">slides</a> and <a href='https://drive.google.com/file/d/1PfYw-o6WlvXOTTGfqBiRju1Ar9yZQNrh/view?usp=drive_link'>code w/ exercises</a>
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 11:30, January 14, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula <b>217</b>,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- Extra for Physicists -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <b>[Extra]. Brief Introduction on Deep Learning: Motivation, Learning as optimisation problem, architectures </b> (2h): <a href="https://docs.google.com/presentation/d/11zBmxxety0St8j_r_gmxrQASLfKblVmxhhBlk_aSUss/edit?usp=sharing">slides</a> and <a href="https://colab.research.google.com/drive/19Wqc2sLNb2or9m-i0w-aOYvh9fZGU2Q-?usp=drive_link">MLP example code</a>, <a href="https://colab.research.google.com/drive/1Z_CBJZ2hrr2rPLhP3Uo5oyfFohewOglr?usp=drive_link">LeNet example code</a>
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 14:30 -- 16:30, January 14, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula <b>220</b>,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- 2 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <b>1. Intro to numerical resolution of Differential Equations </b> (1h+1h): <a href="https://docs.google.com/presentation/d/1kFM3ss1RVbQUZrqWHjLCJXO62_Q8CTwoGIeKoGZg3D0/edit?usp=sharing">slides</a> and <a href="https://colab.research.google.com/drive/1SpSiNCK5ypKA9ze2JiiecQcbknb6j17w?usp=drive_link">exercises code</a>
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 12:30, January 15, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula <b>219</b>,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- 3 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <b>2.Introduction to Physics Informed Neural Networks - Part I forward problems </b> (2h+1h): <a href="https://docs.google.com/presentation/d/11VPimshOxEgA0YRjGFWYgOkea9jSOi16rW6glRRoykQ/edit?usp=drive_link">slides</a> and <a href="https://drive.google.com/file/d/1fEiUy7sPmOeQ-_QuITwZ4anOJDDG8lHO/view?usp=drive_link">example code</a>
          <a href="https://drive.google.com/file/d/1uzM4d6yHgQIpemJp2CEyU1VZOGhE08Rg/view?usp=drive_link">exercise code</a> (<a href="https://drive.google.com/file/d/1-Q5Uaxq8b_dKKR57EaOacDvPbKHrzJkh/view?usp=drive_link">solution code</a> )
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 12:30, January 16, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula 219,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- 4 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
           <i class="far fa-check-square"></i> <b>3. Introduction to Physics Informed Neural Networks - Part II inverse problems and parametric PINNs</b> (2h+1h): <a href="https://docs.google.com/presentation/d/1KINuKSKtQDWAjppxG058FGr-S0pAV6nYGX5JUsTH8rg/edit?usp=drive_link">slides</a> and <a href="https://drive.google.com/file/d/1DWwTVsE7fURD4B6tjl-Dw8RX726GDBkg/view?usp=drive_link">exercise data</a> (<a href="https://drive.google.com/file/d/1buIEgNFe-lKHowSegaJHT_bM2fvDN2gD/view?usp=drive_link"> exercise solution for Heat equation</a>)
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 12:30, January 20, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula 219,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- 5 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <b>4. PINN with nVidia modulus - Part I Introduction & custom PDE</b> (2h+1h): <a href="https://docs.google.com/presentation/d/1hRVbUBHRxY3emwe7Q4hM_RYMLIB64A1SSQjE5TYtJvE/edit?usp=drive_link">slides</a> and <a href="https://drive.google.com/drive/folders/1fhp3F2kDzXn1P1M9-ujDOQG5tnrEb77V?usp=drive_link">code repository</a>
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 12:30, January 22, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula 219,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- 6 -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
          <i class="far fa-check-square"></i> <!--<i class="far fa-square"></i> --> <b>5. PINN with nVidia modulus - Part II custom geometry & different NN architectures</b> (2h+1h): <a href="https://docs.google.com/presentation/d/1066fZ1yVew1FAD-caXJdYpaw9qh-2_tU_3WZeG2OlDQ/edit?usp=drive_link">slides</a> and <a href="https://drive.google.com/drive/folders/1vpXnU7LF8T40fcjS6ohwKlhg2mevWSra?usp=drive_link">code repository</a>
          <br>
          <i pad="10px" class="fa-regular fa-calendar-days" ></i> 09:30 -- 12:30, January 24, 2025.
          <i pad="10px" class="fa-solid fa-map-location-dot"></i> Aula 219,  Plesso Didattico Morgagni - viale Morgagni, 44-48, 50134 Firenze (FI).
      </li>
      <!-- Extra stuff -->
      <li class="list-group-item" style="background-color: inherit; color: inherit;">
        Link to enrollment form: <a href="../pinn-form-2024">Mirror 1</a> <a href="https://forms.gle/waufiF6kEwTRsveK9">Mirror 2</a> (either one of the two is ok)
        <p><i class="fa-regular fa-folder-open"></i> Link to Google Drive Course Folder: <a href="https://drive.google.com/drive/folders/1ygSBGFuxDIxU5rhb68Wd5mxmaSVHhG9z?usp=sharing">mirror 1</a> </p>
        <p><i class="fa-brands fa-git-alt"></i> Link to  Baltig (INFN gitlab) repository: <a href="https://baltig.infn.it/bombini/pinn-course-2024.git">mirror 1</a> </p>
        <p> <i class="fa-solid fa-newspaper"></i> Useful updated list of relevant papers: <a href="https://github.com/bitzhangcy/Neural-PDE-Solver">Neural PDE Solver</a> </p>
        <p><i class="fa-brands fa-git-alt"></i> Useful tutorial to install (old version) nVidia modulus on Colab (not mine): <a href="https://www.youtube.com/watch?v=IcbIFFV8ysk">video</a> and <a href="https://colab.research.google.com/gist/josealvarez97/33fe9b646e63dc20bbf07f562060b83f/nvidia-modulus-installation-on-google-colab.ipynb">colab</a> (<a href="https://colab.research.google.com/drive/1ZSYlaN9hgOvODQDNa0VGyC5uarOy_KH-?usp=sharing">colab mirror 2</a>) </p>
        <p style="text-align: center;"><b>Lectures will be streamed on Discord <i class="fa-brands fa-discord"></i></b> <a href="https://discord.gg/t9MEXgyhAw">Invite link to "PINN Course 2024-2025" discord server</a></p>
      </li>
    </ul>
  </div>
</div>

