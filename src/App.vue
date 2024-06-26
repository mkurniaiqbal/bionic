<template>
  <div class="container">
    <div class="row mt-2 nav nav-tabs">
      <div class="col-6">
        <div class="row me-2 ">
          <button class="nav-link warna-belakang border border-warning active mb-2" id="nav-home-tab"
            data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home"
            aria-selected="true">Marketing Planner</button>
          <button class="nav-link warna-belakang border border-warning mb-2" id="nav-profile-tab" data-bs-toggle="tab"
            data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile"
            aria-selected="false">UI/UX Content Planner</button>
          <button class="nav-link warna-belakang border border-warning mb-2" id="nav-hr-tab" data-bs-toggle="tab"
            data-bs-target="#nav-hr" type="button" role="tab" aria-controls="nav-hr"
            aria-selected="false">HR/Legal Manager</button>
        </div>
      </div>
      <div class="col-6">
        <div class="row ms-2">
          <button class="nav-link warna-belakang border border-warning mb-2" id="nav-ui-tab" data-bs-toggle="tab"
            data-bs-target="#nav-ui" type="button" role="tab" aria-controls="nav-ui" aria-selected="true">UI/UX Content
            Crator</button>

          <button class="nav-link warna-belakang border border-warning mb-2" id="nav-writer-tab" data-bs-toggle="tab"
            data-bs-target="#nav-writer" type="button" role="tab" aria-controls="nav-writer"
            aria-selected="false">UI/UX Design</button>

          <button class="nav-link warna-belakang border border-warning mb-2" id="nav-java-tab" data-bs-toggle="tab"
            data-bs-target="#nav-java" type="button" role="tab" aria-controls="nav-java" aria-selected="false">Java
            Spring Boot</button>
        </div>
      </div>
    </div>
    <div class="tab-content row border border-warning mt-3 px-4 warna-belakang" id="nav-tabContent">
      <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">Marketing Planner</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Monitor competition to identify new industry trends and opportunities for innovation</li>
          <li>Develop marketing strategies based on customer preferences, business objectives, and available resources
          </li>
          <li>Conduct market research to identify potential customers and assess their needs, interests, and preferences
          </li>
          <li>Work with design teams to develop marketing materials such as brochures, ads, and presentations</li>
          <li>Create an advertising budget that reflects the company’s priorities while remaining within the parameters
            set by upper management</li>
          <li>Develop an effective communications strategy for each campaign using several different channels, including
            social media, email, push notification, print ads</li>
          <li>Create a detailed timeline of all marketing activities, including production schedules, deadlines for
            materials delivery, and event dates and locations</li>
          <li>Provide feedback to superiors regarding the effectiveness of new campaigns and recommend adjustments</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Minimum bachelor degree in Marketing Management;</li>
          <li>Minimum 3-5 years experience as Marketing Manager/Director in any marketplace industry;</li>
          <li>Good time management and project management skill;</li>
          <li>Creative communication skill in both verbal and design</li>
          <li>Multi-language abilities in verbal and non-verbal</li>
        </ul>
        <Form />
      </div>

      <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">UI/UX Content Writer</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Performing exhaustive research to gain in-depth knowledge of all customer personas</li>
          <li>Performing extensive research and analysis on consumer thoughts and trends</li>
          <li>Creating specifications and content appropriate for the brand's customer personas</li>
          <li>Strategizing content pillars and sub pillars</li>
          <li>Planning the editorial calendar and content proposition</li>
          <li>Collaborating with content management teams, creative teams, and writers to implement the strategy</li>
          <li>Overseeing writing style and tone for all content</li>
          <li>Developing content governance guidelines for tone, style, and voice of all content, and ensuring they are
            followed</li>
          <li>Developing editorial strategy, so content is consistent across all delivery platforms</li>
          <li>Conducting periodic content audits</li>
          <li>Tracking and calculating content ROI</li>
          <li>Ensuring that content strategy meets business objectives</li>
          <li>Strategizing and improving content delivery and promotion</li>
          <li>Analyzing content marketing strategy to evaluate whether it's working or not.</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Excellent&nbsp;copywriting skills&nbsp;</li>
          <li>Content presentation skills&nbsp;</li>
          <li>Content delivery skills&nbsp;</li>
          <li>Have experience in handling and strategizing marketing campaigns</li>
          <li>Content monetization skills&nbsp;</li>
          <li>Multitasking and organizational skills</li>
          <li>Editorial competency Good analytical abilities to spot patterns and trends in content marketing data</li>
        </ul>
        <Form />

      </div>

      <div class="tab-pane fade" id="nav-hr" role="tabpanel" aria-labelledby="nav-hr-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">HR/Legal Manage</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Have a good understanding in backend app and REST API server development,</li>
          <li>Have a good knowledge in Java Spring Boot, and MVC concept,</li>
          <li>Good understanding in java web application deployment and configuration,</li>
          <li>Good understanding in database query, experience in schema design, query optimization is a great plus,
          </li>
          <li>Have an experience in infrastructure like AWS or Azure and Docker or Kubernetes is a plus.</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Bash Shell</li>
          <li>Java</li>
          <li>Spring Boot</li>
          <li>Java Spring Boot</li>
          <li>Kubernetes &amp; Docker</li>
        </ul>
        <Form />

      </div>

      <div class="tab-pane fade" id="nav-ui" role="tabpanel" aria-labelledby="nav-ui-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">UI/UX Content Writer</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Gather and evaluate user requirements in collaboration with product managers and engineers</li>
          <li>Illustrate design ideas using storyboards, process flows and sitemaps</li>
          <li>Design graphic user interface elements, like menus, tabs and widgets</li>
          <li>Build page navigation buttons and search fields</li>
          <li>Develop UI mockups and prototypes that clearly illustrate how sites function and look like</li>
          <li>Create original graphic designs (e.g. images, sketches and tables)</li>
          <li>Prepare and present rough drafts to internal teams and key stakeholders</li>
          <li>Identify and troubleshoot UX problems (e.g. responsiveness)</li>
          <li>Conduct layout adjustments based on user feedback</li>
          <li>Adhere to style standards on fonts, colors and images</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Proven work experience as a UI/UX Designer or similar role</li>
          <li>Portfolio of design projects</li>
          <li>Knowledge of wireframe tools&nbsp;</li>
          <li>Up-to-date knowledge of design software&nbsp;</li>
          <li>Team spirit; strong communication skills to collaborate with various stakeholders</li>
          <li>Good time-management skills</li>
        </ul>
        <Form />

      </div>

      <div class="tab-pane fade" id="nav-writer" role="tabpanel" aria-labelledby="nav-writer-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">UI/UX Designer</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Gather and evaluate user requirements in collaboration with product managers and engineers</li>
          <li>Illustrate design ideas using storyboards, process flows and sitemaps</li>
          <li>Design graphic user interface elements, like menus, tabs and widgets</li>
          <li>Build page navigation buttons and search fields</li>
          <li>Develop UI mockups and prototypes that clearly illustrate how sites function and look like</li>
          <li>Create original graphic designs (e.g. images, sketches and tables)</li>
          <li>Prepare and present rough drafts to internal teams and key stakeholders</li>
          <li>Identify and troubleshoot UX problems (e.g. responsiveness)</li>
          <li>Conduct layout adjustments based on user feedback</li>
          <li>Adhere to style standards on fonts, colors and images</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Proven work experience as a UI/UX Designer or similar role</li>
          <li>Portfolio of design projects</li>
          <li>Knowledge of wireframe tools&nbsp;</li>
          <li>Up-to-date knowledge of design software&nbsp;</li>
          <li>Team spirit; strong communication skills to collaborate with various stakeholders</li>
          <li>Good time-management skills</li>
        </ul>
        <Form />
      </div>

      <div class="tab-pane fade" id="nav-java" role="tabpanel" aria-labelledby="nav-java-tab" tabindex="0">
        <h2 class="warna-text-header mt-3">Java Spring Boot</h2>
        <br>
        <h5><strong>Job Description :</strong></h5>
        <ul>
          <li>Have a good understanding in backend app and REST API server development,</li>
          <li>Have a good knowledge in Java Spring Boot, and MVC concept,</li>
          <li>Good understanding in java web application deployment and configuration,</li>
          <li>Good understanding in database query, experience in schema design, query optimization is a great plus,
          </li>
          <li>Have an experience in infrastructure like AWS or Azure and Docker or Kubernetes is a plus.</li>
        </ul>
        <h5><strong>Skill :</strong></h5>
        <ul>
          <li>Bash Shell</li>
          <li>Java</li>
          <li>Spring Boot</li>
          <li>Java Spring Boot</li>
          <li>Kubernetes &amp; Docker</li>
        </ul>
        <Form />
      </div>
    </div>
  </div>
</template>

<script setup>
import Form from './components/form/form.vue';
</script>
<style scoped>

.warna-belakang {
  background-color: #f0ebe6;
}

.warna-text-header {
  color: #6a8c58;
}
</style>