<template>
  <div>
    <section class="section split right">
      <section class="section centered">
        <section class="resume-section">
          <p class="is-size-3 r-title">About Me</p>
          <p class="is-size-6 r-title"><a href="http://linkedin.com/in/jarrettandrulis">Linkedin</a> | <a href="http://github.com/jarrettandrulis">Github</a> | <a href="mailto:jarrettandrulis@gmail.com">Email</a> | <a href="../assets/Resume.pdf">Resume</a> </p>
        </section>
        <section class="resume">
          <section class="resume-section">
            <p class="is-size-3 r-title">Work Experience:</p>
            <p class="is-size-5 r-subtitle"><b>Amazon Web Services - Chicago, IL</b></p>
            <p class="is-size-7 r-subtitle">AWS Technical Intern - ProServe | June 2019 - August 2019</p>
            <p class="is-size-5 r-subtitle"><b>R.J. O'Brien - Chicago, IL</b></p>
            <p class="is-size-7 r-subtitle"> Operations Intern | May 2018 - August 2018</p>
            <p class="is-size-5 r-subtitle"><b>R.J. O'Brien - Chicago, IL</b></p>
            <p class="is-size-7 r-subtitle"> Operations Intern | June 2017 - August 2017, December 2017 - January 2018</p>
          </section>

          <section class="resume-section">
            <p class="is-size-3 r-title">Skills:</p>
            <p class="is-size-5 r-subtitle"><b>Programming Languages:</b></p>
            <p class="is-size-7 r-subtitle"> C/C++ | C# | Java | Python | HTML | CSS | Javascript | R</p>
            <p class="is-size-5 r-subtitle"><b>Frameworks:</b></p>
            <p class="is-size-7 r-subtitle">Android | Visual Studio | Vue | Bootstrap | .Net | Excel | React</p>
            <p class="is-size-5 r-subtitle"><b>Concepts:</b></p>
            <p class="is-size-7 r-subtitle">AWS | Microservices | Serverless | Agile Development</p>
          </section>

          <section class="resume-section">
            <p class="is-size-3 r-title">Education and Certificates:</p>
            <p class="is-size-5 r-subtitle"><b>Purdue University</b></p>
            <p class="is-size-7 r-subtitle"> B.S. Computer Science | Certificate in Entrepreneurship | 2016-2020</p>
            <p class="is-size-5 r-subtitle"><b><a href="https://www.certmetrics.com/amazon/public/badge.aspx?i=1&t=c&d=2019-07-03&ci=AWS00938998">AWS Certified Solution's Architect - Associate</a></b></p>
            <p class="is-size-7 r-subtitle"> Valid July 2019 - July 2022</p>
          </section>

        </section>
      </section>
    </section>
  </div>
</template>

<script>

export default {
  name: 'LeftPane',
  components: {
  },
  data () {
    return {
    }
  },
  methods:
  {
  }
}
</script>
<style>
  .right {
    right: 0;
  }
  .centered {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
  }
  .r-title {
    font-family:'Montserrat';
    margin-bottom:0;
  }
  .r-subtitle {
    font-family:'Montserrat';
    margin:0;
  }
  .resume {
    text-align: left;
  }
  .resume-section {
    margin-bottom: 3%;

  }
</style>
