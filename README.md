

<!---
XerxesIXMizel/XerxesIXMizel is a ✨ special ✨ repository because its `README.md` (this <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Logo Header</title>
</head>
<style>
    /* Reset body margins */
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

/* Header Styling */
.header {
    background-image: linear-gradient(to right, #1a3047, #559de6);
    color: white;
    width: 100%;
    padding: 10px 20px;
    display: flex;
    align-items: center;
    box-sizing: border-box;
}

.logo-containerone {
    display: flex;
    align-items: center;
    gap: 20px;
}

.logoone {
    height: 50px;
    width: auto;
}

#dynamic-title {
    font-size: 1.5rem;
    margin: 0;
}

/* Sidebar Styling */
.sidebarone {
    width: 250px;
    background-color: #2c3e50;
    color: white;
    height: 100vh;
    padding-top: 0px;
    position: fixed;
    left: 0;
    top: 70px; /* Offset for the header */
    transition: width 0.3s ease;
    overflow: hidden;
}

.sidebarone.collapsed {
    width: 60px;
}

.sidebarone .toggle-btnone {
    position: relative;
    top: 10px;
    left: 10px;
    width: 40px;
    height: 40px;
    background-color: #2c3e50;
    border: none;
    color: white;
    cursor: pointer;
    font-size: 18px;
}

.sidebarone ul {
    list-style-type: none;
    padding: 0;
    margin-top: 20px;
}

.sidebarone ul li {
    padding: 10px 20px;
    border-bottom: 1px solid #34495e;
}

.sidebarone ul li:last-child {
    border-bottom: none;
}

.sidebarone ul li a {
    color: white;
    text-decoration: none;
    display: block;
}

.sidebarone ul li a:hover {
    background-color: #34495e;
}

.sidebarone ul.hidden {
    display: none;
}

/* Content Styling */
.contentone {
    margin-left: 250px;
    padding: 20px;
    transition: margin-left 0.3s ease;
}

.sidebarone.collapsed + .contentone {
    margin-left: 60px;
}

.section {
    display: none;
}

.section.active {
    display: block;
}


/* ANNOUNCEMENT STYLE */


.announcementbody {
                    font-family: Arial, sans-serif;
                    background-color: #f9f9f9;
                }
        
                .announcementcontainer {
                    max-width: 600px;
                    margin: auto;
                    background: #fff;
                    padding: 20px;
                    border-radius: 8px;
                    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
                }
        
                .announcementform-group {
                    margin-bottom: 15px;
                }
        
                .announcementform-group label {
                    display: block;
                    margin-bottom: 5px;
                    color: #555;
                }
        
                .announcementform-group input, .announcementform-group textarea {
                    width: 100%;
                    padding: 10px;
                    border: 1px solid #ddd;
                    border-radius: 4px;
                    font-size: 14px;
                }
        
                .announcementform-group textarea {
                    resize: vertical;
                }
        
                button {
                    padding: 10px 20px;
                    background-color: #007bff;
                    color: #fff;
                    border: none;
                    border-radius: 4px;
                    cursor: pointer;
                }
        
                button:hover {
                    background-color: #0056b3;
                }
        
                .announcement {
                    border: 1px solid #ddd;
                    padding: 15px;
                    margin-bottom: 10px;
                    border-radius: 4px;
                    background-color: #fdfdfd;
                }
        
                .announcement-header {
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                }
        
                .announcement-header h3 {
                    margin: 0;
                }
        
                .announcementactions button {
                    margin-left: 5px;
                    background-color: #28a745;
                }
        
                .announcementactions button.delete {
                    background-color: #dc3545;
                }
        
                .announcementactions button:hover {
                    opacity: 0.8;
                }
        
                .expired {
                    opacity: 0.6;
                    background-color: #f8d7da;
                }
        
                .announcementedit-section {
                    margin-top: 10px;
                    border-top: 1px solid #ddd;
                    padding-top: 10px;
                }
        
                .announcementedit-section input,
                .announcementedit-section textarea {
                    margin-bottom: 10px;
                    width: calc(100% - 20px);
                    padding: 8px;
                }
        
                .announcementsearch-bar {
                    margin-bottom: 15px;
                }
        
                .announcementsearch-bar input {
                    width: calc(100% - 20px);
                    padding: 10px;
                    border: 1px solid #ddd;
                    border-radius: 4px;
                }


/* FACULTY LOAD STYLE */


                .FLbody {
                    font-family: Arial, sans-serif;
                    margin: 0;
                    padding: 0;
                    display: flex;
                    justify-content: center;
                    align-items: flex-start;
                    height: 100vh;
                    background-color: #f4f4f4;
                }
        
                .FLcontainer {
                    width: 90%;
                    max-width: 1200px;
                    margin-top: 20px;
                }
        
                .FLbutton-container {
                    margin-bottom: 20px;
                    display: flex;
                    justify-content: space-between;
                    width: 100%;
                }
        
                .FLbutton-container button {
                    padding: 20px;
                    margin: 0 10px;
                    cursor: pointer;
                    background-color: #4CAF50;
                    color: white;
                    border: none;
                    border-radius: 10px;
                    width: 48%;
                }
        
                .FLbutton-container button:hover {
                    background-color: #45a049;
                }
        
                .FLform-container {
                    margin-bottom: 20px;
                }
        
                input, select, button {
                    padding: 10px;
                    margin: 5px 0;
                    width: calc(100% - 20px);
                    border-radius: 5px;
                    border: 1px solid #ccc;
                }
        
                button {
                    cursor: pointer;
                    background-color: #4CAF50;
                    color: white;
                    border: none;
                }
        
                button:hover {
                    background-color: #45a049;
                }
        
                table {
                    width: 100%;
                    padding: 10px;
                    background-color: #fff;
                    border-radius: 8px;
                    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                    border-collapse: collapse;
                    margin-top: 20px;
                }
        
                th, td {
                    padding: 10px;
                    text-align: left;
                    border: 1px solid #ddd;
                }
        
                th {
                    background-color: #f4f4f4;
                }
        
                .FLaction-buttons {
                    display: flex;
                    justify-content: space-between;
                }
        
                .FLaction-buttons button {
                    margin: 0 5px;
                }
        
                #course-selector option {
                    display: inline-block;
                    width: calc(100% - 30px); /* Adjust width to leave space for the delete button */
                }
        
                .FLdropdown-buttons {
                    display: flex;
                    justify-content: space-between;
                }


/* SCHEDULE AND SECTION STYLE */


.SScontainer {
      margin-top: 20px;
      max-width: 1200px;
    }

    .SScard {
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .SSsection-divider {
      margin: 40px 0;
    }

    .SStable-container {
      max-height: 300px;  /* Adjust as needed */
      overflow-y: auto;
    }

    
                /* TEACHERS EVALUATION STYLE */


                .TEbody {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.TEcontainer {
  background-color: #fff;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 600px;
  border-radius: 8px;
}

.TEform-group {
  margin-bottom: 15px;
}

</style>
<body>
    <div class="header">
        <div class="logo-containerone">
            <img src="SPCClogo.png" alt="Logo" class="logoone">
            <h1 id="dynamic-title">Welcome to SPCC Portal</h1>
        </div>
    </div>
    <div id="sidebarone" class="sidebarone">
        <button class="toggle-btnone" onclick="toggleSidebarone()">☰</button>
        <ul id="menu">
            <li><a href="#" onclick="showSection('Announcement')">Announcement</a></li>
            <li><a href="#" onclick="showSection('Faculty-Load')">Faculty Load</a></li>
            <li><a href="#" onclick="showSection('Grade-Report')">Grade Report</a></li>
            <li><a href="#" onclick="showSection('Curriculum-Config')">Curriculum Config</a></li>
            <li><a href="#" onclick="showSection('Schedule-Section')">Schedule and Section</a></li>
            <li><a href="#" onclick="showSection('Teachers-Eva')">Teachers Evaluation</a></li>
        </ul>
    </div>
    <div class="contentone">
        <section id="Announcement" class="section active">
            <h1>Announcement</h1>
        <body class="announcementbody">
            <div class="announcementcontainer">
                <!-- Add Announcement Form -->
                <div class="announcementform-group">
                    <label for="title">Title</label>
                    <input type="text" id="title" placeholder="Enter announcement title">
                </div>
                <div class="announcementform-group">
                    <label for="description">Description</label>
                    <textarea id="description" placeholder="Enter announcement description"></textarea>
                </div>
                <div class="announcementform-group">
                    <label for="deadline">Deadline</label>
                    <input type="datetime-local" id="deadline">
                </div>
                <button onclick="addAnnouncement()">Add Announcement</button>
                
                <br>
                <br>
                
                        <!-- Search Bar -->
                <div class="announcementsearch-bar">
                    <input type="text" id="search" placeholder="Search announcements..." onkeyup="filterAnnouncements()">
                </div>
        
        
                <!-- Announcements List -->
                <div id="announcements"></div>
            </div>
        
            <script>
                const announcements = [];
        
                function addAnnouncement() {
                    const title = document.getElementById('title').value;
                    const description = document.getElementById('description').value;
                    const deadline = document.getElementById('deadline').value;
        
                    if (!title || !description || !deadline) {
                        alert('Please fill in all fields.');
                        return;
                    }
        
                    const id = Date.now();
                    const announcement = { id, title, description, deadline };
                    announcements.push(announcement);
        
                    renderAnnouncements();
                    document.getElementById('title').value = '';
                    document.getElementById('description').value = '';
                    document.getElementById('deadline').value = '';
                }
        
                function renderAnnouncements(filtered = announcements) {
                    const announcementcontainer= document.getElementById('announcements');
                    announcementcontainer.innerHTML = '';
                    const now = new Date();
        
                    filtered.forEach((announcement) => {
                        const isExpired = new Date(announcement.deadline) < now;
                        const announcementDiv = document.createElement('div');
                        announcementDiv.className = `announcement ${isExpired ? 'expired' : ''}`;
        
                        announcementDiv.innerHTML = `
                            <div class="announcement-header">
                                <h3 id="title-${announcement.id}">${announcement.title}</h3>
                                <div class="announcementactions">
                                    <button onclick="toggleEditSection(${announcement.id})">Edit</button>
                                    <button class="delete" onclick="deleteAnnouncement(${announcement.id})">Delete</button>
                                </div>
                            </div>
                            <p id="description-${announcement.id}">${announcement.description}</p>
                            <small>Deadline: <span id="deadline-text-${announcement.id}">${new Date(announcement.deadline).toLocaleString()}</span></small>
                            <div class="announcementedit-section" id="announcementedit-section-${announcement.id}" style="display: none;">
                                <input type="text" id="edit-title-${announcement.id}" value="${announcement.title}">
                                <textarea id="edit-description-${announcement.id}">${announcement.description}</textarea>
                                <input type="datetime-local" id="edit-deadline-${announcement.id}" value="${announcement.deadline}">
                                <button onclick="saveChanges(${announcement.id})">Save</button>
                                <button onclick="toggleEditSection(${announcement.id})">Cancel</button>
                            </div>
                        `;
        
                        announcementcontainer.appendChild(announcementDiv);
        
                        if (isExpired) {
                            setTimeout(() => deleteAnnouncement(announcement.id), 1000);
                        }
                    });
                }
        
                function toggleEditSection(id) {
                    const editSection = document.getElementById(`announcementedit-section-${id}`);
                    editSection.style.display = editSection.style.display === 'none' ? 'block' : 'none';
                }
        
                function saveChanges(id) {
                    const title = document.getElementById(`edit-title-${id}`).value;
                    const description = document.getElementById(`edit-description-${id}`).value;
                    const deadline = document.getElementById(`edit-deadline-${id}`).value;
        
                    const announcement = announcements.find(a => a.id === id);
                    if (announcement) {
                        announcement.title = title;
                        announcement.description = description;
                        announcement.deadline = deadline;
                        renderAnnouncements();
                    }
                }
        
                function deleteAnnouncement(id) {
                    const index = announcements.findIndex(a => a.id === id);
                    if (index !== -1) {
                        announcements.splice(index, 1);
                        renderAnnouncements();
                    }
                }
        
                function filterAnnouncements() {
                    const searchQuery = document.getElementById('search').value.toLowerCase();
                    const filtered = announcements.filter(announcement =>
                        announcement.title.toLowerCase().includes(searchQuery) ||
                        announcement.description.toLowerCase().includes(searchQuery)
                    );
                    renderAnnouncements(filtered);
                }
            </script>
        </body>
        </section>

        <section id="Faculty-Load" class="section">
            <h1>Faculty Load</h1>
        <body class="FLbody">
        
        <div class="FLcontainer">
            <div class="FLbutton-container">
                <button onclick="toggleView('faculty-course')">Faculty & Course/Subject Saver</button>
                <button onclick="toggleView('faculty-subject')">Faculty Subject Creator</button>
            </div>
        
            <!-- Faculty & Course/Subject Saver -->
            <div id="faculty-course" class="FLform-container">
                <h3>Add Faculty</h3>
                <input type="text" id="faculty-name" placeholder="Faculty Name">
                <input type="email" id="faculty-email" placeholder="Email Address">
                <button onclick="addFaculty()">Save Faculty</button>
        
                <table id="faculty-table">
                    <thead>
                        <tr>
                            <th>Index</th>
                            <th>Faculty Name</th>
                            <th>Email Address</th>
                            <th>Actions</th>
                        </tr>
                    </thead>
                    <tbody>
                        <!-- Faculty records will be inserted here -->
                    </tbody>
                </table>
            </div>
        
            <!-- Faculty Subject Creator -->
            <div id="faculty-subject" class="FLform-container" style="display:none;">
                <h3>Faculty Subject Creator</h3>
                
                <h4>Manage Courses</h4>
                <input type="text" id="new-course" placeholder="New Course/Subject">
                <button onclick="addCourse()">Add Course</button>
        
                <h4>Select Faculty and Course</h4>
                <select id="faculty-selector">
                    <option disabled selected>Select Faculty</option>
                </select>
                <select id="course-selector">
                    <option disabled selected>Select Course/Subject</option>
                </select>
        
                <div class="FLdropdown-buttons">
                    <button onclick="editSelectedCourse()">Edit Selected Course</button>
                </div>
        
                <button onclick="addFacultySubject()">Assign Faculty to Course</button>
        
                <table id="faculty-subject-table">
                    <thead>
                        <tr>
                            <th>Index</th>
                            <th>Faculty Name</th>
                            <th>Assigned Subject</th>
                            <th>Actions</th>
                        </tr>
                    </thead>
                    <tbody>
                        <!-- Assigned subjects will be inserted here -->
                    </tbody>
                </table>
            </div>
        </div>
        
        <script>
            const facultyList = [];
            const courseList = [];
            const facultySubjects = [];
        
            function addFaculty() {
                const facultyName = document.getElementById('faculty-name').value;
                const facultyEmail = document.getElementById('faculty-email').value;
        
                if (!facultyName || !facultyEmail) {
                    alert("Please enter faculty name and email.");
                    return;
                }
        
                facultyList.push({ name: facultyName, email: facultyEmail });
                updateFacultySelector();
                updateFacultyTable();
                document.getElementById('faculty-name').value = '';
                document.getElementById('faculty-email').value = '';
            }
        
            function addCourse() {
                const newCourse = document.getElementById('new-course').value;
        
                if (!newCourse) {
                    alert("Please enter a course/subject.");
                    return;
                }
        
                courseList.push(newCourse);
                updateCourseSelector();
                document.getElementById('new-course').value = '';
            }
        
            function addFacultySubject() {
                const facultyIndex = document.getElementById('faculty-selector').value;
                const courseIndex = document.getElementById('course-selector').value;
        
                if (facultyIndex === "" || courseIndex === "") {
                    alert("Please select both faculty and course.");
                    return;
                }
        
                const facultyName = facultyList[facultyIndex].name;
                const courseName = courseList[courseIndex];
                facultySubjects.push({ facultyName, courseName });
                updateFacultySubjectTable();
            }
        
            function updateFacultySelector() {
                const selector = document.getElementById('faculty-selector');
                selector.innerHTML = "<option disabled selected>Select Faculty</option>";
                facultyList.forEach((faculty, index) => {
                    const option = document.createElement("option");
                    option.value = index;
                    option.textContent = faculty.name;
                    selector.appendChild(option);
                });
            }
        
            function updateCourseSelector() {
                const selector = document.getElementById('course-selector');
                selector.innerHTML = "<option disabled selected>Select Course/Subject</option>";
                courseList.forEach((course, index) => {
                    const option = document.createElement("option");
                    option.value = index;
                    option.textContent = course;
                    selector.appendChild(option);
                });
            }
        
            function updateFacultyTable() {
                const table = document.getElementById('faculty-table').getElementsByTagName('tbody')[0];
                table.innerHTML = '';
                facultyList.forEach((faculty, index) => {
                    const row = document.createElement('tr');
                    row.innerHTML = `<td>${index + 1}</td><td>${faculty.name}</td><td>${faculty.email}</td>
                                     <td class="FLaction-buttons">
                                        <button onclick="editFaculty(${index})">Edit</button>
                                        <button onclick="deleteFaculty(${index})">Delete</button>
                                     </td>`;
                    table.appendChild(row);
                });
            }
        
            function updateFacultySubjectTable() {
                const table = document.getElementById('faculty-subject-table').getElementsByTagName('tbody')[0];
                table.innerHTML = '';
                facultySubjects.forEach((subject, index) => {
                    const row = document.createElement('tr');
                    row.innerHTML = `<td>${index + 1}</td><td>${subject.facultyName}</td><td>${subject.courseName}</td>
                                     <td class="FLaction-buttons">
                                        <button onclick="deleteFacultySubject(${index})">Delete</button>
                                     </td>`;
                    table.appendChild(row);
                });
            }
        
            function toggleView(view) {
                if (view === 'faculty-course') {
                    document.getElementById('faculty-course').style.display = 'block';
                    document.getElementById('faculty-subject').style.display = 'none';
                } else {
                    document.getElementById('faculty-subject').style.display = 'block';
                    document.getElementById('faculty-course').style.display = 'none';
                }
            }
        
            function editFaculty(index) {
                const newFacultyName = prompt("Edit Faculty Name:", facultyList[index].name);
                const newFacultyEmail = prompt("Edit Faculty Email:", facultyList[index].email);
        
                if (newFacultyName && newFacultyEmail) {
                    facultyList[index].name = newFacultyName;
                    facultyList[index].email = newFacultyEmail;
                    updateFacultyTable();
                    updateFacultySelector();
                }
            }
        
            function deleteFaculty(index) {
                facultyList.splice(index, 1);
                updateFacultyTable();
                updateFacultySelector();
            }
        
            function editSelectedCourse() {
                const selectedCourseIndex = document.getElementById('course-selector').value;
                const newCourse = prompt("Edit Course/Subject Name:", courseList[selectedCourseIndex]);
        
                if (newCourse) {
                    courseList[selectedCourseIndex] = newCourse;
                    updateCourseSelector();
                }
            }
        
            function deleteCourse(index) {
                courseList.splice(index, 1);
                updateCourseSelector();
            }
        
            function deleteFacultySubject(index) {
                facultySubjects.splice(index, 1);
                updateFacultySubjectTable();
            }
        
            // Add sample data for testing
            courseList.push("2024-2025 Eng 1 - Purposive Communication", "2024-2025 AnMod - Analytics Modeling", "2024-2025 DiscMath - Discrete Mathematics");
            updateCourseSelector();
        </script>
        </body>
        </section>

        <section id="Grade-Report" class="section">
            <h1>Grade report</h1>
            <body class="GRbody">
                <div class="GRcontainer">
                    <form id="gradeForm">
                        <div class="GRform-group">
                            <label for="subject">Subject:</label>
                            <input type="text" id="subject" name="subject" placeholder="Enter subject" required>
                        </div>
                        <div class="GRform-group">
                            <label for="score">Score:</label>
                            <input type="number" id="score" name="score" min="0" placeholder="Enter achieved score" required>
                        </div>
                        <div class="GRform-group">
                            <label for="highScore">High Score:</label>
                            <input type="number" id="highScore" name="highScore" min="1" placeholder="Enter maximum score" required>
                        </div>
                        <button type="button" id="addGrade">Add Grade</button>
                    </form>
                    <table id="gradeTable">
                        <thead>
                            <tr>
                                <th>Subject</th>
                                <th>Score</th>
                                <th>Percentage (%)</th>
                            </tr>
                        </thead>
                        <tbody></tbody>
                    </table>
                    <div id="reportSummary">
                        <p><strong>Total Percentage:</strong> <span id="totalPercentage">0</span>%</p>
                        <p><strong>Average Percentage:</strong> <span id="averagePercentage">0</span>%</p>
                    </div>
                </div>
                <script>
                document.getElementById('addGrade').addEventListener('click', () => {
                const subject = document.getElementById('subject').value.trim();
                const score = parseFloat(document.getElementById('score').value);
                const highScore = parseFloat(document.getElementById('highScore').value);
            
                if (subject === '' || isNaN(score) || isNaN(highScore) || score < 0 || highScore <= 0 || score > highScore) {
                    alert('Please enter valid subject, score, and high score values.');
                    return;
                }
            
                // Calculate percentage
                const percentage = ((score / highScore) * 100).toFixed(2);
            
                // Add grade to the table
                const tableBody = document.querySelector('#gradeTable tbody');
                const row = tableBody.insertRow();
                row.innerHTML = `
                    <td>${subject}</td>
                    <td>${score} / ${highScore}</td>
                    <td>${percentage}</td>
                `;
            
                // Clear input fields
                document.getElementById('subject').value = '';
                document.getElementById('score').value = '';
                document.getElementById('highScore').value = '';
            
                // Update summary
                updateSummary();
            });
            
            function updateSummary() {
                const percentages = Array.from(document.querySelectorAll('#gradeTable tbody tr td:nth-child(3)'))
                    .map(td => parseFloat(td.textContent));
            
                const totalPercentage = percentages.reduce((sum, percentage) => sum + percentage, 0);
                const averagePercentage = percentages.length > 0 ? (totalPercentage / percentages.length).toFixed(2) : 0;
            
                document.getElementById('totalPercentage').textContent = totalPercentage.toFixed(2);
                document.getElementById('averagePercentage').textContent = averagePercentage;
            }
            
            
                </script>
        </section>

        <section id="Curriculum-Config" class="section">
            <h1>Curriculum</h1>
            <div class="CCcontainer">
                <div class="CCsection">
                    <h1>Curriculum Configuration</h1>
                    <select id="schoolYear">
                        <option value="2024-2025">2024 - 2025</option>
                        <option value="2025-2026">2025 - 2026</option>
                        <option value="2026-2027">2026 - 2027</option>
                        <!-- More school years can be added here -->
                    </select>
                    <button>Set as Subject Curriculum</button>
                    <table>
                        <thead>
                            <tr>
                                <th>No.</th>
                                <th>Description</th>
                                <th>Course Code</th>
                                <th>Lecture</th>
                                <th>Laboratory</th>
                                <th>Units</th>
                                <th>School Year</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1</td>
                                <td>Application Development and Emerging Technologies</td>
                                <td>ADET</td>
                                <td>2</td>
                                <td>1</td>
                                <td>3</td>
                                <td><span id="schoolYearDisplay">2024-2025</span></td>
                            </tr>
                            <tr>
                                <td>2</td>
                                <td>Analytics Modeling</td>
                                <td>AnMod</td>
                                <td>3</td>
                                <td>1</td>
                                <td>4</td>
                                <td><span id="schoolYearDisplay">2024-2025</span></td>
                            </tr>
                            <!-- More rows can be added here -->
                        </tbody>
                    </table>
                </div>
            </div>
        
            <script>
                document.getElementById('schoolYear').addEventListener('change', function() {
                    var selectedYear = this.value;
                    var rows = document.querySelectorAll('tbody tr');
                    
                    rows.forEach(function(row) {
                        row.querySelectorAll('td:last-child span').forEach(function(cell) {
                            cell.textContent = selectedYear;
                        });
                    });
                });
            </script>
        </section>

        <section id="Schedule-Section" class="section">
            <h1>Schedule and Section</h1>
            <div class="SScontainer">
                <header class="text-center mb-4">
                  <h1>Schedule & Section Management</h1>
                  <p>S.Y.: 2024 - 2025</p>
                </header>
            
                <!-- Section Template Management -->
                <div class="row">
                  <div class="col-md-5">
                    <div class="SScard p-3">
                      <h5 class="SScard-title">Add Section Template</h5>
                      <form id="sectionForm">
                        <div class="mb-3">
                          <label for="sectionName" class="form-label">Section Name:</label>
                          <input type="text" class="form-control" id="sectionName" placeholder="Enter section name" required>
                        </div>
                        <div class="mb-3">
                          <label for="selectYear" class="form-label">Select Year:</label>
                          <select class="form-select" id="selectYear" required>
                            <option selected disabled value="">-- Choose Student Year --</option>
                            <option value="1st Year">1st Year</option>
                            <option value="2nd Year">2nd Year</option>
                            <option value="3rd Year">3rd Year</option>
                            <option value="4th Year">4th Year</option>
                          </select>
                        </div>
                        <div class="row mb-3">
                          <div class="col">
                            <label for="minCapacity" class="form-label">Min:</label>
                            <input type="number" class="form-control" id="minCapacity" placeholder="Minimum capacity" required>
                          </div>
                          <div class="col">
                            <label for="maxCapacity" class="form-label">Max:</label>
                            <input type="number" class="form-control" id="maxCapacity" placeholder="Maximum capacity" required>
                          </div>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Save Section Template</button>
                      </form>
                    </div>
                  </div>
            
                  <div class="col-md-7">
                    <div class="SScard p-3">
                      <h5 class="SScard-title">Section Template(s)</h5>
                      <div class="mb-3">
                        <input type="text" class="form-control" id="searchSectionInput" placeholder="Search section templates..." onkeyup="searchSections()">
                      </div>
                      <div class="SStable-container">
                        <table class="table table-bordered table-striped" id="sectionTable">
                          <thead class="table-primary">
                            <tr>
                              <th>No.</th>
                              <th>Name</th>
                              <th>Year</th>
                              <th>Min</th>
                              <th>Max</th>
                            </tr>
                          </thead>
                          <tbody id="sectionTableBody">
                            <!-- Rows will be dynamically added -->
                          </tbody>
                        </table>
                      </div>
                    </div>
                  </div>
                </div>
            
                <!-- Divider -->
                <div class="SSsection-divider"></div>
            
                <!-- Schedule Management -->
                <div class="row">
                  <div class="col-md-6">
                    <div class="SScard p-3">
                      <h5 class="SScard-title">Add Schedule</h5>
                      <form id="scheduleForm">
                        <div class="mb-3">
                          <label for="section-template" class="form-label">Choose Section Template:</label>
                          <select id="section-template" class="form-select" required>
                            <option value="">-- Choose Section Template --</option>
                          </select>
                        </div>
                        <div class="mb-3">
                          <label for="faculty" class="form-label">Choose Faculty/Faculties:</label>
                          <input type="text" class="form-control" id="faculty" placeholder="Enter Faculty Name">
                        </div>
                        <div class="mb-3">
                          <label for="subject" class="form-label">Choose Subject:</label>
                          <input type="text" class="form-control" id="subject" placeholder="Enter Subject Name">
                        </div>
                        <div class="row mb-3">
                          <div class="col">
                            <label for="day" class="form-label">Day:</label>
                            <select id="day" class="form-select">
                              <option value="">-- Select Day --</option>
                              <option value="monday">Monday</option>
                              <option value="tuesday">Tuesday</option>
                              <option value="wednesday">Wednesday</option>
                              <option value="thursday">Thursday</option>
                              <option value="friday">Friday</option>
                            </select>
                          </div>
                          <div class="col">
                            <label for="startTime" class="form-label">Start Time:</label>
                            <input type="time" class="form-control" id="startTime">
                          </div>
                          <div class="col">
                            <label for="endTime" class="form-label">End Time:</label>
                            <input type="time" class="form-control" id="endTime">
                          </div>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Save Schedule</button>
                      </form>
                    </div>
                  </div>
            
                  <div class="col-md-6">
                    <div class="SScard p-3">
                      <h5 class="SScard-title">Assigned Sections</h5>
                      <div class="mb-3">
                        <input type="text" class="form-control" id="searchScheduleInput" placeholder="Search assigned sections..." onkeyup="searchSchedules()">
                      </div>
                      <div class="SStable-container">
                        <table class="table table-bordered">
                          <thead class="table-primary">
                            <tr>
                              <th>No.</th>
                              <th>Section</th>
                              <th>Faculty</th>
                              <th>Subject</th>
                              <th>Day/Time</th>
                            </tr>
                          </thead>
                          <tbody id="scheduleTableBody">
                            <!-- Rows will be dynamically added -->
                          </tbody>
                        </table>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            
              <script>
                const sectionTemplates = [];
                const scheduleEntries = [];
            
                const sectionForm = document.getElementById('sectionForm');
                const sectionTableBody = document.getElementById('sectionTableBody');
                const sectionDropdown = document.getElementById('section-template');
                const searchSectionInput = document.getElementById('searchSectionInput');
            
                const scheduleForm = document.getElementById('scheduleForm');
                const scheduleTableBody = document.getElementById('scheduleTableBody');
                const searchScheduleInput = document.getElementById('searchScheduleInput');
            
                sectionForm.addEventListener('submit', (e) => {
                  e.preventDefault();
                  const name = document.getElementById('sectionName').value;
                  const year = document.getElementById('selectYear').value;
                  const min = document.getElementById('minCapacity').value;
                  const max = document.getElementById('maxCapacity').value;
            
                  sectionTemplates.push({ name, year, min, max });
                  renderSections();
                });
            
                scheduleForm.addEventListener('submit', (e) => {
                  e.preventDefault();
                  const section = document.getElementById('section-template').value;
                  const faculty = document.getElementById('faculty').value;
                  const subject = document.getElementById('subject').value;
                  const day = document.getElementById('day').value;
                  const startTime = document.getElementById('startTime').value;
                  const endTime = document.getElementById('endTime').value;
            
                  scheduleEntries.push({ section, faculty, subject, day, startTime, endTime });
                  renderSchedules();
                });
            
                function renderSections() {
                  sectionTableBody.innerHTML = '';
                  sectionDropdown.innerHTML = '<option value="">-- Choose Section Template --</option>';
                  sectionTemplates.forEach((template, index) => {
                    sectionTableBody.innerHTML += `
                      <tr>
                        <td>${index + 1}</td>
                        <td>${template.name}</td>
                        <td>${template.year}</td>
                        <td>${template.min}</td>
                        <td>${template.max}</td>
                      </tr>`;
                    sectionDropdown.innerHTML += `<option value="${template.name}">${template.name} (${template.year})</option>`;
                  });
                }
            
                function renderSchedules() {
                  scheduleTableBody.innerHTML = '';
                  scheduleEntries.forEach((entry, index) => {
                    scheduleTableBody.innerHTML += `
                      <tr>
                        <td>${index + 1}</td>
                        <td>${entry.section}</td>
                        <td>${entry.faculty}</td>
                        <td>${entry.subject}</td>
                        <td>${entry.day} ${entry.startTime} - ${entry.endTime}</td>
                      </tr>`;
                  });
                }
            
                function searchSections() {
                  const filter = searchSectionInput.value.toLowerCase();
                  const rows = sectionTableBody.getElementsByTagName('tr');
                  Array.from(rows).forEach((row) => {
                    const name = row.cells[1].textContent.toLowerCase();
                    const year = row.cells[2].textContent.toLowerCase();
                    if (name.includes(filter) || year.includes(filter)) {
                      row.style.display = '';
                    } else {
                      row.style.display = 'none';
                    }
                  });
                }
            
                function searchSchedules() {
                  const filter = searchScheduleInput.value.toLowerCase();
                  const rows = scheduleTableBody.getElementsByTagName('tr');
                  Array.from(rows).forEach((row) => {
                    const section = row.cells[1].textContent.toLowerCase();
                    const faculty = row.cells[2].textContent.toLowerCase();
                    const subject = row.cells[3].textContent.toLowerCase();
                    if (section.includes(filter) || faculty.includes(filter) || subject.includes(filter)) {
                      row.style.display = '';
                    } else {
                      row.style.display = 'none';
                    }
                  });
                }
              </script>
        </section>

<section id="Teachers-Eva" class="section">
    <body class="TEbody">
        <div class="TEcontainer">
          <form id="evaluationForm">
            <div class="TEform-group">
              <label for="teacherName">Teacher's Name:</label>
              <input type="text" id="teacherName" name="teacherName" required>
            </div>
            <div class="TEform-group">
              <label for="subject">Subject Taught:</label>
              <input type="text" id="subject" name="subject" required>
            </div>
            <div class="TEform-group">
              <label for="effectiveness">Teacher's Effectiveness:</label>
              <select id="effectiveness" name="effectiveness" required>
                <option value="1">1 - Poor</option>
                <option value="2">2 - Fair</option>
                <option value="3">3 - Good</option>
                <option value="4">4 - Very Good</option>
                <option value="5">5 - Excellent</option>
              </select>
            </div>
            <div class="TEform-group">
              <label for="clarity">Clarity of Teaching:</label>
              <select id="clarity" name="clarity" required>
                <option value="1">1 - Poor</option>
                <option value="2">2 - Fair</option>
                <option value="3">3 - Good</option>
                <option value="4">4 - Very Good</option>
                <option value="5">5 - Excellent</option>
              </select>
            </div>
            <div class="TEform-group">
              <label for="communication">Communication Skills:</label>
              <select id="communication" name="communication" required>
                <option value="1">1 - Poor</option>
                <option value="2">2 - Fair</option>
                <option value="3">3 - Good</option>
                <option value="4">4 - Very Good</option>
                <option value="5">5 - Excellent</option>
              </select>
            </div>
            <div class="TEform-group">
              <label for="comments">Additional Comments:</label>
              <textarea id="comments" name="comments" rows="4" placeholder="Any additional feedback?"></textarea>
            </div>
            <button type="submit">Submit Evaluation</button>
          </form>
          <div id="resultMessage"></div>
        </div>
      
        <script>
        document.getElementById('evaluationForm').addEventListener('submit', function(event) {
        event.preventDefault();
      
        const teacherName = document.getElementById('teacherName').value;
        const subject = document.getElementById('subject').value;
        const effectiveness = document.getElementById('effectiveness').value;
        const clarity = document.getElementById('clarity').value;
        const communication = document.getElementById('communication').value;
        const comments = document.getElementById('comments').value;
      
        // Check if all required fields are filled
        if (teacherName && subject && effectiveness && clarity && communication) {
          const resultMessage = `Thank you for your evaluation of ${teacherName} teaching ${subject}. Here are your responses:\n
                                 Teacher's Effectiveness: ${effectiveness}\n
                                 Clarity of Teaching: ${clarity}\n
                                 Communication Skills: ${communication}\n
                                 Additional Comments: ${comments || 'None'}`;
      
          document.getElementById('resultMessage').textContent = 'Evaluation Submitted Successfully!';
          alert(resultMessage);
        } else {
          document.getElementById('resultMessage').textContent = 'Please fill in all required fields.';
        }
      });
      
        </script>
      </body>
            
        </section>
    </div>

    <script>
        function toggleSidebarone() {
            const sidebar = document.getElementById('sidebarone');
            const menu = document.getElementById('menu');

            // Toggle the visibility of the menu
            menu.classList.toggle('hidden');

            // Change button appearance
            if (menu.classList.contains('hidden')) {
                sidebarone.classList.add('collapsed');
            } else {
                sidebarone.classList.remove('collapsed');
            }
        }

        function showSection(sectionId) {
            const sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                if (section.id === sectionId) {
                    section.classList.add('active');
                    updateTitle(sectionId); // Update the dynamic title
                } else {
                    section.classList.remove('active');
                }
            });
        }

        function updateTitle(sectionId) {
            const titleMap = {
                'Announcement': 'Announcement',
                'Faculty-Load': 'Faculty Load',
                'Grade-Report': 'Grade Report',
                'Curriculum-Config': 'Curriculum Config',
                'Schedule-Section': 'Schedule and Section',
                'Teachers-Eva': 'Teachers Evaluation'
            };
            const title = document.getElementById('dynamic-title');
            title.textContent = titleMap[sectionId] || 'Welcome to SPCC Portal';
        }
    </script>
</body>
</html>
file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
