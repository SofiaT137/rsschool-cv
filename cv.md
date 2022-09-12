# Sofiya Tkachenia

## Contacts:
- Location: Minsk
- E-mail: sofiatkachenia@gmail.com


## About Me:
I am a Java developer studying frontend technologies. My strengths are fast learning, great teamwork and a passion for development.


## Skills: 
 - _Backend technologies_: Tomcat, Java(8 and 11), Spring, Spring Boot, Hibernate
- _Frontend technologies_: HTML 5, CSS 3, Javascript, React
- _CI-CD_: Jenkins
- _Databases_: MySQL, PostgreSQL
- _AWS_: EC2, RDS, S3, IAM
- _VCS_: Git


## Code examples:

 __Tower of Hanoi__ (https://en.wikipedia.org/wiki/Tower_of_Hanoi)

```javascript

 function towerHanoi(disks) {
  let stackA = [];
  let stackB = [];
  let stackC = [];
  let number = 0;

  for (let t = disks; t > 0; t--) {
    stackA.push(t);
  }

  runHanoi(disks, stackA, stackB, stackC);

  function runHanoi(z, A, B, C) {
    if (z == 1) {
      B.push(A.pop());
      number++;
    } else {
      runHanoi(z - 1, A, C, B);
      B.push(A.pop());
      number++;
      runHanoi(z - 1, C, B, A);
    }
  }
  return number;
}
```

## Education:
- Bachelor of Engineering, International Sakharov Environmental Institute (BSU), Minsk:
    - Environmental Monitoring Faculty
- JWD, EPAM: Basic knowlage of Java, Tomcat, MySQl, HTML, CSS
- MJC-School, EPAM: Advanced knowlage of Java, MySQL, Spring, Hibernate, HTML, CSS, JavaScript, React.


## Work experience:
Full development of the REST API, including database design, backend and frontend of the application.


## Languages:
- Russian: Native speaker
- Belarusian: Native speaker
- English: B1
- Spanish: A1


