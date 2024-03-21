<head>
  <style>
    body {
      font-family: tahoma;
      text-align: center;
    }
    header {
      letter-spacing: 6px;
      background-color: royalblue;
      padding: 20px;
      color: white;
    }
    h2 {
      font-size: 2em;
      width: 100%;
    }
    section {
      padding: 30px;
      margin-bottom: 40px;
    }
    .container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .card {
      border: 1px solid #ccc;
      background-color: ivory;
      margin: 25px;
      padding: 25px;
      box-shadow: 6px 6px 6px rgba(0, 0, 0, 0.3);
    }
    .icons {
      font-size: 8em;
      padding: 25px;
    }
    button, .button {
      background: royalblue;
      border: 0;
      color: white;
      padding: 10px;
      width: 100%;
      margin-bottom: 10px;
    }
    td{
      padding:10px;
      }
    table{
      margin:auto;
      }
    
    @media screen and min width: 50em) {
      .card {
        flex-basis: 325px;
      }
      header h1 {
        font-size: 5em;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Adrian Coders Inc.</h1>
    <h4>Programming at its peak!</h4>
  </header>
  <section>
    <h2>WELCOME:The best programmers ready to help you achieve your dreams using programinng langauges to develop applications,websites,learn and also pursue your dream job</h2>
    <p>VISION: Where programmers come together to develop their talents,skills and become better versions of themsevles and those around them</p>
    <br><br>
    <p>ABOUT US:Adrian CodersInc, was fouded in January 2024 by Adrian Edmundson.We have served and worked with 50 persons whose dream is to learn how to code and also pursue alot more intheir career with programming.Out of the 50 people we have worked with,20 0f them have become succesefull programmers and have taken off jobs as computer programmers,computer network architects,Software developers,web developers and database administrators.</p>
  </section>
  <section class="container">
    <h2>OUR SERVICES: </h2>
    <article class="card">
      <div class="icons"> &#10084;</div>
      <h3>Adrian Edmundson (He/Him) </h3>
      <p>Executuve Director,Founder and Software Engineer - Sets the overall vision, strategy, and direction of the company. Provides leadership to the team, make key decisions about resource allocation, hiring, and business priorities. Is accountable for the company's success and growth,navigates challenges, mitigates risks, and capitalizes on opportunities to drive the business forward
As part of the Programming company, he also takes part in designing, developing, testing, and maintaining software applications or systems by working with team members to understand requirements, write code using programming languages, debug and troubleshoot issues to ensure the software meets quality standards and deadlines.</p>
      <button> Contact </button>
    </article>
    <article class="card">
      <div class="icons"> &#10084;</div>
      <h3>Onesmus Wack(He/Him</h3>
      <p>Sofware architect/web developer- Creates and designs websites and takes charge of overall look and feel. He  handles the technical aspects of a website, including its performance (speed) and capacity (the maximum amount of traffic the site could handle at a given time).He also designs the overall structure of a software system, defining the architecture and ensuring that it meets technical and business needs</p>
      <button> Contact </button
      <article class="card"></article>
    <div class="icons">&#10084;</div>
       <h3>Diane Makumbi(She/Her</h3>
      <p> Project manager-Oversees the planning, execution, and delivery of software projects, managing resources, timelines, and budgets to ensure successful outcomes.</p>
    <button>Contact</button>
    </article>
  </section>
        <Section>
          <h2>List of activities we do and how they can help our stakeholders:<h2>
            <form id="my-form">
            <table>
              <tr>
                <td>Activities:</td>
                <td><input type="text" size="25"activity="my-activity"> </td>
              </tr>
              <tr>
                <td>Benefits:</td>
                <td><input type="text"size="25" benefit="my-benefits"></td>
              </tr>
              <tr>
                <td>Activities you would like:</td>
                <td>
                  <select name="activities of choice">
                    <option>Software development</option>
                    <option>Web development</option>
                    <option>Software architect</option>
                    <option>project managment</option>
                    <option>Overall software engineering</option>
                  </select>
                </td>
              </tr>
              
              <tr>
                <td>Rate us out of 10:</td>
                <td><input type="number name="out of10" value="0" min="1" max="10"></td>
                  <small>(max10)</small>
              </tr>
              <tr>
                    <br>
                      </tr>
                    <tr>
                      <td colspan="2">
                        <input class= "button" type="button" value="Submit">
                          <input class="button" type="reset"value="Clear">
                      </td>
                    </tr>
              
            </table>
              </form>
</body>
  
                  
                  
                  &copy:Copyright Adrian Edmundson@2024.Inc.
