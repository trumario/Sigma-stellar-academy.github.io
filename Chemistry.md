<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chemistry for Teens: 8th-9th Grade</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">
  <!-- Header -->
  <header class="bg-blue-600 text-white py-6">
    <div class="container mx-auto px-4">
      <h1 class="text-3xl font-bold">Chemistry for Teens: 8th-9th Grade</h1>
      <p class="mt-2 text-lg">Explore the exciting world of chemistry with hands-on experiments and fun activities!</p>
    </div>
  </header>

  <!-- Navigation -->
  <nav class="bg-blue-800 text-white py-4">
    <div class="container mx-auto px-4 flex justify-center space-x-6">
      <a href="#welcome" class="hover:underline">Welcome</a>
      <a href="#curriculum" class="hover:underline">Curriculum</a>
      <a href="#students" class="hover:underline">For Students</a>
      <a href="#quiz" class="hover:underline">Quiz</a>
      <a href="#parents" class="hover:underline">For Parents</a>
      <a href="#resources" class="hover:underline">Resources</a>
    </div>
  </nav>

  <!-- Welcome Section -->
  <section id="welcome" class="py-10 container mx-auto px-4">
    <h2 class="text-2xl font-bold mb-4">Welcome to Chemistry!</h2>
    <p class="text-lg mb-4">This webpage is your hub for the 8th-9th grade chemistry curriculum. Students, dive into atoms, reactions, and real-world science! Parents, learn how this course sparks curiosity and prepares your teen for high school.</p>
    <img src="https://images.unsplash.com/photo-1621293954908-907159247272?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=300&q=80" alt="Chemistry Lab" class="w-full h-64 object-cover rounded-lg mb-4">
  </section>

  <!-- Curriculum Overview -->
  <section id="curriculum" class="py-10 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl font-bold mb-4">Curriculum Overview</h2>
      <p class="mb-4">Our 36-week chemistry course introduces teens to the science of matter through fun lessons and safe experiments. Here’s what we cover:</p>
      <ul class="list-disc pl-6 mb-4">
        <li><strong>Unit 1: Intro to Chemistry</strong> (Weeks 1-8): Learn about matter, states, and the scientific method.</li>
        <li><strong>Unit 2: Atoms & Elements</strong> (Weeks 9-16): Explore atoms, the periodic table, and molecules.</li>
        <li><strong>Unit 3: Chemical Reactions</strong> (Weeks 17-26): Discover how substances transform, including acids and bases.</li>
        <li><strong>Unit 4: Chemistry in the World</strong> (Weeks 27-36): Connect chemistry to the environment, medicine, and more.</li>
      </ul>
      <p>Students will do hands-on labs, projects like a “Chemistry Fair,” and explore real-world applications.</p>
    </div>
  </section>

  <!-- For Students -->
  <section id="students" class="py-10 container mx-auto px-4">
    <h2 class="text-2xl font-bold mb-4">For Students: Your Chemistry Adventure</h2>
    <p class="mb-4">Get excited to learn chemistry with these actionable steps! Check your weekly tasks, try safe experiments at home, and explore cool resources.</p>

    <!-- Weekly Task Tracker -->
    <h3 class="text-xl font-semibold mb-2">Weekly Task Tracker</h3>
    <p class="mb-4">Select the current week to see your assignment and resources.</p>
    <select id="weekSelector" class="p-2 border rounded mb-4">
      <option value="1">Week 1: What is Chemistry?</option>
      <option value="2">Week 2: Scientific Method</option>
      <option value="3">Week 3: States of Matter</option>
      <option value="4">Week 4: Physical vs. Chemical Changes</option>
      <option value="5">Week 5: Density and Buoyancy</option>
      <option value="6">Week 6: Mixtures vs. Pure Substances</option>
      <option value="7">Week 7: Lab Safety and Review</option>
      <option value="8">Week 8: Unit 1 Assessment</option>
      <option value="9">Week 9: What Are Atoms?</option>
      <option value="10">Week 10: The Periodic Table</option>
      <option value="11">Week 11: Elements in Everyday Life</option>
      <option value="12">Week 12: Atomic Structure</option>
      <option value="13">Week 13: Intro to Chemical Bonding</option>
      <option value="14">Week 14: Molecules and Compounds</option>
      <option value="15">Week 15: Lab Week—Exploring Elements</option>
      <option value="16">Week 16: Unit 2 Assessment</option>
      <option value="17">Week 17: What is a Chemical Reaction?</option>
      <option value="18">Week 18: Signs of a Chemical Reaction</option>
      <option value="19">Week 19: Balancing Equations</option>
      <option value="20">Week 20: Types of Reactions</option>
      <option value="21">Week 21: Acids and Bases</option>
      <option value="22">Week 22: Neutralization Reactions</option>
      <option value="23">Week 23: Chemistry in Cooking</option>
      <option value="24">Week 24: Lab Week—Reaction Rates</option>
      <option value="25">Week 25: Review and Mini-Project</option>
      <option value="26">Week 26: Unit 3 Assessment</option>
      <option value="27">Week 27: Chemistry in the Environment</option>
      <option value="28">Week 28: Chemistry in Industry</option>
      <option value="29">Week 29: Chemistry in Medicine</option>
      <option value="30">Week 30: Conservation of Matter</option>
      <option value="31">Week 31: Interdisciplinary Chemistry</option>
      <option value="32">Week 32: Lab Week—Fun Chemistry</option>
      <option value="33">Week 33: Final Project Prep</option>
      <option value="34">Week 34: Final Project Prep</option>
      <option value="35">Week 35: Chemistry Fair</option>
      <option value="36">Week 36: Final Review</option>
    </select>
    <div id="weekContent" class="bg-gray-200 p-4 rounded-lg">
      <p>Select a week to view tasks and resources.</p>
    </div>

    <!-- At-Home Experiments -->
    <h3 class="text-xl font-semibold mt-6 mb-2">Try These Safe At-Home Experiments</h3>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <div class="bg-blue-100 p-4 rounded-lg">
        <h4 class="font-semibold">Baking Soda & Vinegar Volcano</h4>
        <p><strong>Materials</strong>: Baking soda, vinegar, dish soap, food coloring, container.</p>
        <p><strong>Steps</strong>: Mix 2 tbsp baking soda, 1 tsp dish soap, and red food coloring in a container. Pour in ½ cup vinegar. Watch the reaction!</p>
        <p><strong>Safety</strong>: Wear goggles, do it in a sink or outside.</p>
        <p><strong>Learn</strong>: This shows a chemical reaction producing carbon dioxide gas.</p>
      </div>
      <div class="bg-blue-100 p-4 rounded-lg">
        <h4 class="font-semibold">Density Tower</h4>
        <p><strong>Materials</strong>: Honey, dish soap, water, oil, glass.</p>
        <p><strong>Steps</strong>: Slowly layer liquids in a glass (honey, soap, water, oil). Drop small objects to see where they float.</p>
        <p><strong>Safety</strong>: Handle carefully, clean spills.</p>
        <p><strong>Learn</strong>: Different liquids have different density.</p>
      </div>
    </div>

    <!-- Interactive Tool -->
    <h3 class="text-xl font-semibold mt-6 mb-2">Explore the Periodic Table</h3>
    <p>Click below to interact with a digital periodic table and learn about elements!</p>
    <a href="https://phet.colorado.edu/sims/html/build-an-atom/latest/build-an-atom_en.html" target="_blank" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Interactive Periodic Table</a>
  </section>

  <!-- Quiz Section -->
  <section id="quiz" class="py-10 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl font-bold mb-4">Test Your Chemistry Knowledge!</h2>
      <p class="mb-4">Try these quizzes to check your understanding of chemistry concepts. Select an answer and get instant feedback!</p>
      <div id="quizContainer" class="bg-gray-200 p-4 rounded-lg">
        <h3 class="text-xl font-semibold mb-2">Sample Quiz: Chemistry Basics</h3>
        <div id="question1" class="mb-4">
          <p class="font-semibold">1. What is the smallest unit of an element?</p>
          <label><input type="radio" name="q1" value="a"> A) Molecule</label><br>
          <label><input type="radio" name="q1" value="b"> B) Atom</label><br>
          <label><input type="radio" name="q1" value="c"> C) Compound</label><br>
          <label><input type="radio" name="q1" value="d"> D) Proton</label><br>
          <button onclick="checkAnswer('q1', 'b', 'Correct! An atom is the smallest unit of an element.', 'Incorrect. The smallest unit of an element is an atom.')" class="bg-blue-600 text-white px-4 py-2 mt-2 rounded hover:bg-blue-700">Submit</button>
          <p id="feedback1" class="mt-2"></p>
        </div>
        <div id="question2" class="mb-4">
          <p class="font-semibold">2. What gas is produced in a baking soda and vinegar reaction?</p>
          <label><input type="radio" name="q2" value="a"> A) Oxygen</label><br>
          <label><input type="radio" name="q2" value="b"> B) Hydrogen</label><br>
          <label><input type="radio" name="q2" value="c"> C) Carbon Dioxide</label><br>
          <label><input type="radio" name="q2" value="d"> D) Nitrogen</label><br>
          <button onclick="checkAnswer('q2', 'c', 'Correct! The reaction produces carbon dioxide gas.', 'Incorrect. The reaction produces carbon dioxide.')" class="bg-blue-600 text-white px-4 py-2 mt-2 rounded hover:bg-blue-700">Submit</button>
          <p id="feedback2" class="mt-2"></p>
        </div>
        <div id="question3" class="mb-4">
          <p class="font-semibold">3. Which of these is a physical change?</p>
          <label><input type="radio" name="q3" value="a"> A) Burning wood</label><br>
          <label><input type="radio" name="q3" value="b"> B) Rusting iron</label><br>
          <label><input type="radio" name="q3" value="c"> C) Melting ice</label><br>
          <label><input type="radio" name="q3" value="d"> D) Baking a cake</label><br>
          <button onclick="checkAnswer('q3', 'c', 'Correct! Melting ice is a physical change.', 'Incorrect. Melting ice is a physical change, not a chemical one.')" class="bg-blue-600 text-white px-4 py-2 mt-2 rounded hover:bg-blue-700">Submit</button>
          <p id="feedback3" class="mt-2"></p>
        </div>
      </div>
    </div>
  </section>

  <!-- For Parents -->
  <section id="parents" class="py-10 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-2xl font-bold mb-4">For Parents: Supporting Your Teen</h2>
      <p class="mb-4">This curriculum is designed to spark curiosity and build skills for high school science. Here’s what you need to know:</p>
      <ul class="list-disc pl-6 mb-4">
        <li><strong>Goals</strong>: Teach foundational chemistry, critical thinking, and safe lab practices.</li>
        <li><strong>Safety</strong>: All experiments are supervised in class with goggles and gloves. At-home experiments use household items (e.g., vinegar, baking soda).</li>
        <li><strong>How to Help</strong>: Encourage your teen to complete weekly tasks, try quizzes, and discuss chemistry in daily life (e.g., cooking).</li>
        <li><strong>Outcomes</strong>: Prepares teens for high school chemistry, biology, and careers in science, medicine, or engineering.</li>
      </ul>
      <p>Contact the teacher via email (placeholder@example.com) for questions.</p>
    </div>
  </section>

  <!-- Resources -->
  <section id="resources" class="py-10 container mx-auto px-4">
    <h2 class="text-2xl font-bold mb-4">Resources</h2>
    <p class="mb-4">Explore these free tools to boost your chemistry learning!</p>
    <ul class="list-disc pl-6">
      <li><a href="https://www.khanacademy.org/science/chemistry" target="_blank" class="text-blue-600 hover:underline">Khan Academy Chemistry</a>: Free videos and quizzes.</li>
      <li><a href="https://phet.colorado.edu/en/simulations/category/chemistry" target="_blank" class="text-blue-600 hover:underline">PhET Simulations</a>: Interactive chemistry labs.</li>
      <li><a href="https://www.youtube.com/c/CrashCourse" target="_blank" class="text-blue-600 hover:underline">Crash Course Chemistry</a>: Fun video lessons.</li>
    </ul>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white py-6">
    <div class="container mx-auto px-4 text-center">
      <p>© 2025 Chemistry for Teens. All rights reserved.</p>
    </div>
  </footer>

  <!-- JavaScript for Weekly Task Tracker and Quiz -->
  <script>
    const weekData = {
      1: { task: "Week 1: What is Chemistry?<br>Task: List 5 examples of chemistry in your home (e.g., cooking, cleaning). Discuss in class.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=FSyAehMdpyI' target='_blank' class='text-blue-600 hover:underline'>Crash Course Chemistry #1</a>." },
      2: { task: "Week 2: Scientific Method<br>Task: Design a simple experiment (e.g., how salt affects water boiling). Write a hypothesis and conclusion.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/states-of-matter-basics/latest/states-of-matter-basics_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET States of Matter</a>." },
      3: { task: "Week 3: States of Matter<br>Task: Draw a comic strip showing water changing states (solid, liquid, gas).<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/states-of-matter-and-intermolecular-forces' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: States of Matter</a>." },
      4: { task: "Week 4: Physical vs. Chemical Changes<br>Task: Find 3 examples of physical and chemical changes at home.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=3VvA3P4uAF0' target='_blank' class='text-blue-600 hover:underline'>Amoeba Sisters: Physical vs. Chemical Changes</a>." },
      5: { task: "Week 5: Density and Buoyancy<br>Task: Create a density tower at home and explain why objects float.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/density/latest/density_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Density Simulation</a>." },
      6: { task: "Week 6: Mixtures vs. Pure Substances<br>Task: Create a poster on mixtures vs. pure substances.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-bonds' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Mixtures</a>." },
      7: { task: "Week 7: Lab Safety and Review<br>Task: Complete a lab safety quiz and review Unit 1 concepts.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=VRWRmIEHr3A' target='_blank' class='text-blue-600 hover:underline'>Lab Safety Video</a>." },
      8: { task: "Week 8: Unit 1 Assessment<br>Task: Complete quiz on states of matter, changes, and density. Present 'Chemistry in My Life' slideshow.<br>Resource: Review <a href='https://www.khanacademy.org/science/chemistry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy Chemistry</a>." },
      9: { task: "Week 9: What Are Atoms?<br>Task: Research one element and its uses.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=0RRVV4Diomg' target='_blank' class='text-blue-600 hover:underline'>Crash Course: The Atom</a>." },
      10: { task: "Week 10: The Periodic Table<br>Task: Memorize 10 common elements (e.g., H, O, C).<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/build-an-atom/latest/build-an-atom_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Build an Atom</a>." },
      11: { task: "Week 11: Elements in Everyday Life<br>Task: Write a short story featuring an element as a character.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/periodic-table' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Periodic Table</a>." },
      12: { task: "Week 12: Atomic Structure<br>Task: Draw atomic diagrams for hydrogen and oxygen.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=6rdmpx39PRk' target='_blank' class='text-blue-600 hover:underline'>Amoeba Sisters: Atomic Structure</a>." },
      13: { task: "Week 13: Intro to Chemical Bonding<br>Task: Research water (H₂O) as a molecule.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/molecule-shapes/latest/molecule-shapes_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Molecule Shapes</a>." },
      14: { task: "Week 14: Molecules and Compounds<br>Task: Build molecule models (e.g., water, CO₂) with candy.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=4eC9Ni1Xwos' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Molecules</a>." },
      15: { task: "Week 15: Lab Week—Exploring Elements<br>Task: Write a lab report on observing element properties.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-bonds' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Chemical Bonds</a>." },
      16: { task: "Week 16: Unit 2 Assessment<br>Task: Complete quiz on atoms and periodic table. Present 'Periodic Table Superhero' project.<br>Resource: Review <a href='https://www.khanacademy.org/science/chemistry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy Chemistry</a>." },
      17: { task: "Week 17: What is a Chemical Reaction?<br>Task: Write a description of a chemical reaction you observe.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=0Bt6RPP2ANI' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Chemical Reactions</a>." },
      18: { task: "Week 18: Signs of a Chemical Reaction<br>Task: List 3 reactions seen in daily life.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/reactions-and-rates/latest/reactions-and-rates_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Reactions</a>." },
      19: { task: "Week 19: Balancing Equations<br>Task: Complete a worksheet on simple chemical equations.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=2S6e11NBwiw' target='_blank' class='text-blue-600 hover:underline'>Amoeba Sisters: Balancing Equations</a>." },
      20: { task: "Week 20: Types of Reactions<br>Task: Classify 5 reactions from class demos.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-reactions-stoichiometry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Reaction Types</a>." },
      21: { task: "Week 21: Acids and Bases<br>Task: Create a pH scale chart using household items.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/ph-scale/latest/ph-scale_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET pH Scale</a>." },
      22: { task: "Week 22: Neutralization Reactions<br>Task: Research antacids and neutralization.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=Oj-5gWm1-HA' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Acids and Bases</a>." },
      23: { task: "Week 23: Chemistry in Cooking<br>Task: Explain a cooking reaction (e.g., baking soda in cookies).<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-reactions-stoichiometry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Reactions</a>." },
      24: { task: "Week 24: Lab Week—Reaction Rates<br>Task: Graph results of Alka-Seltzer reaction rate lab.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/reactions-and-rates/latest/reactions-and-rates_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Reaction Rates</a>." },
      25: { task: "Week 25: Review and Mini-Project<br>Task: Design a poster on a favorite chemical reaction.<br>Resource: Review <a href='https://www.khanacademy.org/science/chemistry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy Chemistry</a>." },
      26: { task: "Week 26: Unit 3 Assessment<br>Task: Complete quiz on reactions and pH. Present 'Kitchen Chemistry' demo.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=Oj-5gWm1-HA' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Acids and Bases</a>." },
      27: { task: "Week 27: Chemistry in the Environment<br>Task: Research a local environmental chemistry issue.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-reactions-stoichiometry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Reactions</a>." },
      28: { task: "Week 28: Chemistry in Industry<br>Task: Write a paragraph on plastic recycling.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=FwCwcHjSEkA' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Polymers</a>." },
      29: { task: "Week 29: Chemistry in Medicine<br>Task: Research the chemistry of aspirin or another medicine.<br>Resource: Read <a href='https://www.khanacademy.org/science/chemistry/chemical-bonds' target='_blank' class='text-blue-600 hover:underline'>Khan Academy: Chemical Bonds</a>." },
      30: { task: "Week 30: Conservation of Matter<br>Task: Write a lab report on a closed-system reaction.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=0Bt6RPP2ANI' target='_blank' class='text-blue-600 hover:underline'>Crash Course: Chemical Reactions</a>." },
      31: { task: "Week 31: Interdisciplinary Chemistry<br>Task: Explain a biochemical reaction (e.g., photosynthesis).<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/molecules-and-light/latest/molecules-and-light_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Molecules and Light</a>." },
      32: { task: "Week 32: Lab Week—Fun Chemistry<br>Task: Explain the chemistry of slime or elephant toothpaste.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=1htB7N3Ane4' target='_blank' class='text-blue-600 hover:underline'>Slime Chemistry Video</a>." },
      33: { task: "Week 33: Final Project Prep<br>Task: Start designing your Chemistry Fair demo.<br>Resource: Review <a href='https://www.khanacademy.org/science/chemistry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy Chemistry</a>." },
      34: { task: "Week 34: Final Project Prep<br>Task: Continue working on your Chemistry Fair demo.<br>Resource: Try <a href='https://phet.colorado.edu/sims/html/reactions-and-rates/latest/reactions-and-rates_en.html' target='_blank' class='text-blue-600 hover:underline'>PhET Reaction Rates</a>." },
      35: { task: "Week 35: Chemistry Fair<br>Task: Present your Chemistry Fair demo to the class.<br>Resource: Watch <a href='https://www.youtube.com/watch?v=FSyAehMdpyI' target='_blank' class='text-blue-600 hover:underline'>Crash Course Chemistry #1</a>." },
      36: { task: "Week 36: Final Review<br>Task: Review all units and prepare for the final quiz. Play Chemistry Jeopardy in class!<br>Resource: Review <a href='https://www.khanacademy.org/science/chemistry' target='_blank' class='text-blue-600 hover:underline'>Khan Academy Chemistry</a>." }
    };

    const weekSelector = document.getElementById('weekSelector');
    const weekContent = document.getElementById('weekContent');
    weekSelector.addEventListener('change', () => {
      const week = weekSelector.value;
      const content = weekData[week] ? weekData[week].task : "Select a week to view tasks and resources.";
      weekContent.innerHTML = content;
    });

    function checkAnswer(questionId, correctAnswer, correctMessage, incorrectMessage) {
      const selected = document.querySelector(`input[name="${questionId}"]:checked`);
      const feedback = document.getElementById(`feedback${questionId.slice(1)}`);
      if (selected && selected.value === correctAnswer) {
        feedback.innerHTML = `<span class="text-green-600">${correctMessage}</span>`;
      } else {
        feedback.innerHTML = `<span class="text-red-600">${incorrectMessage}</span>`;
      }
    }
  </script>
</body>
</html>
