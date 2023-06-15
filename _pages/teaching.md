---
layout: page
title: Teaching
permalink: /teaching/
---

## Instructorship @ Boğaziçi University

- Turkish Language and Culture Program Grammar Instructor (syllabi will be available soon)
- Turkish Language and Culture Program Speaking Instructor, [Summer 2022](https://furkandikmen.com/assets/syllabus/S20_Speaking_Summer_2022 İzlence.pdf) 

## Teaching Assistanships @ Boğaziçi University

.popup {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      display: none;
      justify-content: center;
      align-items: center;
    }

    .popup-content {
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      max-width: 400px;
    }
  </style>
  <script>
    function showPopup(semester) {
      var popup = document.getElementById('popup');
      var popupContent = document.getElementById('popup-content');
      popupContent.innerHTML = getCourseList(semester);
      popup.style.display = 'flex';
    }

    function closePopup() {
      var popup = document.getElementById('popup');
      popup.style.display = 'none';
    }

    function getCourseList(semester) {
      // Replace with your own course data or fetch it from an external source
      var courseData = {
        '2019 Spring': ['Course A', 'Course B', 'Course C'],
        '2019 Fall': ['Course D', 'Course E', 'Course F'],
        '2020 Spring': ['Course G', 'Course H', 'Course I'],
        '2020 Fall': ['Course J', 'Course K', 'Course L'],
        '2021 Spring': ['Course M', 'Course N', 'Course O'],
        '2021 Fall': ['Course P', 'Course Q', 'Course R'],
        '2022 Spring': ['Course S', 'Course T', 'Course U'],
        '2022 Fall': ['Course V', 'Course W', 'Course X'],
        '2023 Spring': ['Course Y', 'Course Z'],
      };

      var courses = courseData[semester] || [];
      var courseListHTML = '<h2>' + semester + ' Courses</h2>';

      if (courses.length > 0) {
        courseListHTML += '<ul>';
        courses.forEach(function (course) {
          courseListHTML += '<li>' + course + '</li>';
        });
        courseListHTML += '</ul>';
      } else {
        courseListHTML += '<p>No courses found for this semester.</p>';
      }

      return courseListHTML;
    }
  </script>
</head>
<body>
  <h1>Course List</h1>

  <ul>
    <li><a href="#" onclick="showPopup('2019 Spring')">2019 Spring</a></li>
    <li><a href="#" onclick="showPopup('2019 Fall')">2019 Fall</a></li>
    <li><a href="#" onclick="showPopup('2020 Spring')">2020 Spring</a></li>
    <li><a href="#" onclick="showPopup('2020 Fall')">2020 Fall</a></li>
    <li><a href="#" onclick="showPopup('2021 Spring')">2021 Spring</a></li>
    <li><a href="#" onclick="showPopup('2021 Fall')">2021 Fall</a></li>
    <li><a href="#" onclick="showPopup('2022 Spring')">2022 Spring</a></li>
    <li><a href="#" onclick="showPopup('2022 Fall')">2022 Fall</a></li>
    <


- LING101 (Introduction to Language and Linguistics I) Spring 2023, [Spring 2022](https://furkandikmen.com/assets/syllabus/LING101_Spring 2022.pdf), [Fall 2021](https://furkandikmen.com/assets/syllabus/LING101_Fall2021.pdf), [Spring 2021](https://furkandikmen.com/assets/syllabus/LING 101_Spring2021.pdf), [Fall 2020](https://furkandikmen.com/assets/syllabus/LING101 _Fall2020.pdf), [Fall 2019](https://furkandikmen.com/assets/syllabus/LING101_Fall2019.pdf)

- LING102 (Introduction to Language and Linguistics II) Spring 2022, Spring 2021, Spring 2019

- LING203 (Syntax) [Fall 2022](https://furkandikmen.com/assets/syllabus/LING203_FALL2022.pdf), [Fall 2019](https://furkandikmen.com//assets/syllabus/LING203_FALL2019.pdf)

- LING305 (Semantics) [Fall 2022](https://furkandikmen.com/assets/syllabus/Ling305_Fall2022.pdf), [Fall 2021](https://furkandikmen.com/assets/syllabus/Ling305_Fall2021 Syllabus.pdf),[Fall 2022](https://furkandikmen.com/assets/syllabus/LING305Fall2020.pdf), Fall 2019

- LING313 (Phonology and Morphology of Modern Turkish) [Fall 2020](https://furkandikmen.com/assets/syllabus/LING313_Fall2020.pdf)

- LING314 (Syntax and Semantics of Modern Turkish) Spring 2023, [Spring 2020](https://furkandikmen.com/assets/syllabus/LING314_Spring2020.pdf)

- LING340 (Advanced Syntax) Spring 2021
