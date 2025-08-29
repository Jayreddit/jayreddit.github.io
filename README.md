<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>20‑Question Quiz</title>
    <style>
        body {
            background: #0b0f14;
            color: #e5e7eb;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .quiz-container {
            background: #1a1f29;
            padding: 20px;
            max-width: 800px;
            width: 100%;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
        }
        
        h1 {
            text-align: center;
            color: #7c5cff;
        }
        
        .question {
            margin-bottom: 15px;
        }
        
        .options label {
            display: block;
            background: #2a2f3c;
            padding: 8px;
            border-radius: 8px;
            margin: 6px 0;
            cursor: pointer;
        }
        
        .options input {
            margin-right: 8px;
        }
        
        button {
            background: #7c5cff;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
        }
        
        button:hover {
            background: #6445d4;
        }
        
        #result {
            margin-top: 20px;
            font-size: 20px;
            text-align: center;
            font-weight: bold;
            color: #00e676;
        }
    </style>
</head>

<body>
    <div class="quiz-container">
        <h1>Technology in Teaching and Learning</h1>
        <p style="text-align:center; font-size:18px; font-weight:bold; margin-top:10px;">
            1 take only and you have 45 minutes to answer. Good luck and God bless.
        </p>

        <form id="quizForm">

            <!-- Example Question (replace with your own) -->
            <div class="question">
                <p> This teaching method are often teacher-centered, focusing on memorization and recitation
                </p>
                <div class="options">
                    <label><input type="radio" name="q1" value="a"> Technology</label>
                    <label><input type="radio" name="q1" value="b"> Modern</label>
                    <label><input type="radio" name="q1" value="c"> ICT</label>
                    <label><input type="radio" name="q1" value="d"> Traditional</label>
                    <!-- Example: -->
                </div>
            </div>

            <!-- Duplicate & Edit for Questions 2–20 -->
            <!-- Example: -->
            <div class="question">
                <p> This domain demonstrate awareness of policies affecting ICT in education
                </p>
                <div class="options">
                    <label><input type="radio" name="q2" value="a"> Domain 2 Curriculum and Assessment</label>
                    <label><input type="radio" name="q2" value="b"> Domain 1 Understanding ICT in Education</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q2" value="c"> Domain 3 Pedagogy</label>
                    <label><input type="radio" name="q2" value="d"> Domain 4 Technology Tools</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> This domain apply relevant technology tools for classroom activities</p>
                <div class="options">
                    <label><input type="radio" name="q3" value="a"> Domain 7 Teacher Disposition</label>
                    <label><input type="radio" name="q3" value="b"> Domain 5 Organization and Administration</label>
                    <label><input type="radio" name="q3" value="c"> Domain 2 Curriculum and Assessment</label>
                    <label><input type="radio" name="q3" value="d"> Domain 3 Pedagogy</label>
                    <!-- Example: -->
                </div>
            </div>

            <!-- Repeat until Question 20 -->

            <div class="question">
                <p> This means that teachers demonstrate a sound understanding of technology operations and concepts
                </p>
                <div class="options">
                    <label><input type="radio" name="q4" value="a"> Assessment and Evaluation</label>
                    <label><input type="radio" name="q4" value="b"> Teaching, Learning and Curriculum</label>
                    <label><input type="radio" name="q4" value="c"> Technology and Operations and Concepts</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q4" value="d"> Productivity and Professional Practice</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> This international organization for educational technology called ___________.</p>
                <div class="options">
                    <label><input type="radio" name="q5" value="a"> ICT COMPETENCY STANDARDS </label>
                    <label><input type="radio" name="q5" value="b"> International Society for Technology in Education</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q5" value="c"> Technology Tools </label>
                    <label><input type="radio" name="q5" value="d"> Department of Information Communication and Technology</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Refers to a mix of process and product used in the application of knowledge. </p>
                <div class="options">
                    <label><input type="radio" name="q6" value="a"> Technology Tools</label>
                    <label><input type="radio" name="q6" value="b"> Productivity Tools</label>
                    <label><input type="radio" name="q6" value="c"> Email Tools</label>
                    <label><input type="radio" name="q6" value="d"> Technology</label>
                    <!-- Example: -->
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> An editable website usually with limited access, allows students to collaboratively create and post written work or digital files</p>
                <div class="options">
                    <label><input type="radio" name="q7" value="a"> Wiki</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q7" value="b"> Podcast</label>
                    <label><input type="radio" name="q7" value="c"> Blog</label>
                    <label><input type="radio" name="q7" value="d"> Vlog</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Is an online journal where posted information from both teachers and students are arranged. </p>
                <div class="options">
                    <label><input type="radio" name="q8" value="a"> Multimedia</label>
                    <label><input type="radio" name="q8" value="b"> Blog</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q8" value="c"> Wiki</label>
                    <label><input type="radio" name="q8" value="d"> Vlog</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> ___________ is an instrument used for doing work. It can be anything that help you accomplish your goal with the use of technology. </p>
                <div class="options">
                    <label><input type="radio" name="q9" value="a"> Email Tools</label>
                    <label><input type="radio" name="q9" value="b"> Technology Tools</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q9" value="c"> Data/Calculation Tools</label>
                    <label><input type="radio" name="q9" value="d"> Design Tools</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> A structured, inquiry-oriented activity where students primarily use online resources to investigate a central, open-ended question
                </p>
                <div class="options">
                    <label><input type="radio" name="q10" value="a"> Webquest</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q10" value="b"> Flipped classroom</label>
                    <label><input type="radio" name="q10" value="c"> Digital Learning</label>
                    <label><input type="radio" name="q10" value="d"> Digital Literacy</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Software or applications that allow users to perform calculations and computations on data</p>
                <div class="options">
                    <label><input type="radio" name="q11" value="a"> Design Tools</label>
                    <label><input type="radio" name="q11" value="b"> Email Tools</label>
                    <label><input type="radio" name="q11" value="c"> Handheld Devices</label>
                    <label><input type="radio" name="q11" value="d"> Data/Calculation Tools</label>
                    <!-- Example: -->
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> This type of Web only consists 4% of the internet and publicly accessible using google and bing</p>
                <div class="options">
                    <label><input type="radio" name="q12" value="a"> World Wide Web</label>
                    <label><input type="radio" name="q12" value="b"> The Deep Web</label>
                    <label><input type="radio" name="q12" value="c"> The Surface Web</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q12" value="d"> The Dark Web</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> It is the use of variety of media formats given in a presentation or self-study program.</p>
                <div class="options">
                    <label><input type="radio" name="q13" value="a"> Podcast</label>
                    <label><input type="radio" name="q13" value="b"> Multimedia</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q13" value="c"> Vlog</label>
                    <label><input type="radio" name="q13" value="d"> Blog</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Software applications and programs that function without requiring a continous internet connection</p>
                <div class="options">
                    <label><input type="radio" name="q14" value="a"> Offline Digital Tools</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q14" value="b"> Online Digital Tools</label>
                    <label><input type="radio" name="q14" value="c"> Productivity Tools</label>
                    <label><input type="radio" name="q14" value="d"> Email tools</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> refers to the physical, tangible tools and equipment used in the educational process</p>
                <div class="options">
                    <label><input type="radio" name="q15" value="a"> Hardware</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q15" value="b"> Technology</label>
                    <label><input type="radio" name="q15" value="c"> Software</label>
                    <label><input type="radio" name="q15" value="d"> application</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Refers to the use of technology in teaching and learning. </p>
                <div class="options">
                    <label><input type="radio" name="q16" value="a"> Instructional Technology</label>
                    <label><input type="radio" name="q16" value="b"> Digital Literacy</label>
                    <label><input type="radio" name="q16" value="c"> Educational Technology</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q16" value="d"> ICT Literacy</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Is a massive network of networks, a networking infrastructure.</p>
                <div class="options">
                    <label><input type="radio" name="q17" value="a"> Internet</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q17" value="b"> Web Access</label>
                    <label><input type="radio" name="q17" value="c"> World Wide Web</label>
                    <label><input type="radio" name="q17" value="d"> Multimedia</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> refers to the portion of the internet that is not indexed by standard search engines like Google or Bing.
                </p>
                <div class="options">
                    <label><input type="radio" name="q18" value="a"> The Surface Web</label>
                    <label><input type="radio" name="q18" value="b"> The Deep Web</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q18" value="c"> The Dark Web</label>
                    <label><input type="radio" name="q18" value="d"> None of the Above</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Is the ability of the learner to access the internet during lesson to take advantage of available educational resources.
                </p>
                <div class="options">
                    <label><input type="radio" name="q19" value="a"> VoIP</label>
                    <label><input type="radio" name="q19" value="b"> Web Access</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q19" value="c"> Facebook</label>
                    <label><input type="radio" name="q19" value="d"> Instructional Technology</label>
                </div>
            </div>

            <!-- Repeat until Question 20 -->
            <div class="question">
                <p> Refer to any type of software associated with computers and related technologies that can be used as tools for personal</p>
                <div class="options">
                    <label><input type="radio" name="q20" value="a"> Productivity Tools</label>
                    <!-- Example: -->
                    <label><input type="radio" name="q20" value="b"> Email Tools</label>
                    <label><input type="radio" name="q20" value="c"> Discussion Tools</label>
                    <label><input type="radio" name="q20" value="d"> Design Tools</label>
                </div>
            </div>




            <button type="submit">Submit Quiz</button>
        </form>
        <div id="result"></div>
    </div>

  <style>
    /* ✅ Modal Styles */
    .modal {
        display: none; /* Hidden by default */
        position: fixed;
        z-index: 9999;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        background: rgba(0,0,0,0.7);
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .modal-content {
        background: #1a1f29;
        padding: 25px;
        border-radius: 12px;
        text-align: center;
        color: #e5e7eb;
        width: 350px;
        box-shadow: 0 0 15px rgba(0,0,0,0.5);
        animation: popIn 0.3s ease;
    }

    .modal-content h2 {
        margin-bottom: 15px;
        color: #7c5cff;
    }

    .close-btn {
        margin-top: 15px;
        padding: 10px 20px;
        background: #7c5cff;
        color: white;
        border: none;
        border-radius: 8px;
        cursor: pointer;
    }

    .close-btn:hover {
        background: #6445d4;
    }

    @keyframes popIn {
        from { transform: scale(0.8); opacity: 0; }
        to { transform: scale(1); opacity: 1; }
    }
</style>

<!-- ✅ Modal HTML -->
<div id="scoreModal" class="modal">
    <div class="modal-content">
        <h2>Quiz Completed!</h2>
        <p id="modalScore"></p>
        <button class="close-btn" onclick="closeModal()">Close</button>
    </div>
</div>
<script>
    // ✅ Correct Answers
    const correctAnswers = {
        q1: "d", q2: "b", q3: "d", q4: "c", q5: "b",
        q6: "d", q7: "a", q8: "b", q9: "b", q10: "a",
        q11: "d", q12: "c", q13: "b", q14: "a", q15: "a",
        q16: "c", q17: "a", q18: "b", q19: "b", q20: "a"
    };

    let submitted = false;

    // 🔀 Shuffle helper
    function shuffleArray(array) {
        for (let i = array.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [array[i], array[j]] = [array[j], array[i]];
        }
        return array;
    }

    // ✅ Shuffle Questions + Options
    window.addEventListener("DOMContentLoaded", () => {
        const quizForm = document.getElementById("quizForm");
        const questions = Array.from(quizForm.querySelectorAll(".question"));

        shuffleArray(questions);

        questions.forEach(q => {
            // shuffle the options inside each question
            const options = Array.from(q.querySelectorAll("label"));
            shuffleArray(options);
            options.forEach(opt => q.querySelector(".options").appendChild(opt));

            // re-append question
            quizForm.insertBefore(q, quizForm.querySelector("button[type=submit]"));
        });
    });

    // ✅ Submit Event
    document.getElementById("quizForm").addEventListener("submit", function(e) {
        e.preventDefault();
        if (submitted) return;
        submitted = true;

        let score = 0;
        let total = 20;

        for (let i = 1; i <= total; i++) {
            const qName = "q" + i;
            const answer = document.querySelector(`input[name="${qName}"]:checked`);
            const correct = correctAnswers[qName];

            document.querySelectorAll(`input[name="${qName}"]`).forEach(opt => {
                const label = opt.parentElement;

                if (opt.value === correct) {
                    label.style.background = "#1b5e20"; 
                    label.style.color = "white";
                }

                if (answer && opt === answer && opt.value !== correct) {
                    label.style.background = "#b71c1c"; 
                    label.style.color = "white";
                }
            });

            if (answer && answer.value === correct) {
                score++;
            }
        }

        // Show score
        document.getElementById("result").innerText = `You scored ${score} out of ${total}`;

        // ✅ Show modal
        document.getElementById("modalScore").innerText = `You scored ${score} out of ${total}`;
        document.getElementById("scoreModal").style.display = "flex";

        // 🔒 Lock quiz
        document.querySelectorAll("input[type=radio]").forEach(input => input.disabled = true);
        document.querySelector("button[type=submit]").disabled = true;
    });

    function closeModal() {
        document.getElementById("scoreModal").style.display = "none";
    }

    // 🚨 Anti-cheating Reset
    function resetQuiz() {
        document.getElementById("quizForm").reset();
        document.getElementById("result").innerText = "";
        submitted = false;

        // Reset styles
        document.querySelectorAll("label").forEach(label => {
            label.style.background = "";
            label.style.color = "";
        });

        // Unlock quiz
        document.querySelectorAll("input[type=radio]").forEach(input => input.disabled = false);
        document.querySelector("button[type=submit]").disabled = false;

        alert("⚠️ HALLA KA NAG SESEARCH KA RESET KA SAKEN MEN!");
    }

    document.addEventListener("visibilitychange", () => {
        if (document.hidden && !submitted) {
            resetQuiz();
        }
    });

    window.addEventListener("blur", () => {
        if (!submitted) {
            resetQuiz();
        }
    });
</script>



</body>

</html>
