




@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');


body {

    /* DO NOT CHANGE THESE */
    font-family: Verdana, Arial, sans-serif;
}

.hamburger{
  align-items: flex-end;
}

.fa-bars{
  color: rgb(22,100,100);
  text-decoration: none;
  font-size: 3em;
  transition: transform 1s linear, color 4s linear;
  text-align: right;
  width: 1em;
}

.hamburger:active{
  color:  rgb(0 200 200)
}

aside .hamburger {
  text-align: right;
}

.fa-bars:active{
    color: rgb (200, 30, 30);
    transform: rotate(90deg);
}



footer {

    /* DO NOT CHANGE THESE */
    background-color: #444444;
    color: #eeeeee;
  }

header{
width: 100%;
border-radius: 1em 1em 0 0;
}

.hero {
    /* DO NOT CHANGE THESE */
    background-color: #444444;
  }

.hero h1 {
      /* DO NOT CHANGE THESE */
      color: #ffffff;
      width: 30%;
      font-size: 1em;
      padding-top: 1em;
    }

header ul{
  list-style-type: none;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  flex: 0 0 30%;
  margin: 0 0 0 0;

}

header li:hover{
    color: rgb (200, 30, 30);
  }

header ul li{
    flex: 0 0 7%;
    margin-right: 1em;
    padding-bottom: .5em;
}

section{
display: flex;
}

/* Body around Articles and Sections */
.container{
  width: 100%;
  display: inline-block;

}

/* Group of ARTICLEs 1-6 */
section main{
  display: flex;
  flex-wrap: wrap;
  height: 100%;
  width: 96%;
  align-items:center;
}
.posts {
        /* DO NOT CHANGE THESE */
        color: #444444;
      }

      /* Indiviudal ARTICLEs 1-6 */
section main article{
  flex: 0 0 100%;
  margin: 2%;
}
.posts article {

          /* DO NOT CHANGE THESE */
          background-color: #dddddd;
          border: 1px solid #444444;
          height: 10em; /* this is just so we can see the articles since they have no content */
      }

/* SIDEBAR GROUP 1-3 */
aside{
  display: flex;
  flex-direction: column;
  flex: 0 0 25%;
  height: 100%;
  padding-left: 1em;
  padding-right: 1em;
}
.sidebar {

          /* DO NOT CHANGE THESE */
          background-color: #aaaaaa;
          color: #444444;
}
.sidebar section {
    /* DO NOT CHANGE THESE */
    background-color: #dddddd;
    border: 1px solid #444444;
    height: 10em; /* this is just so we can see the articles since they have no content */
    margin-top: 1em;
}

/* Indiviudal Sidebars 1-3 */
aside section{
  margin-bottom: 1em;

}






footer{
  border: 1px solid rgb(0, 0, 255);
  width: 100%;
  border-radius: 0 0 1em 1em;
}
footer nav{
  width: 50%;
  margin-left: 2em;
}

p{
  width: 100%;
  font-size: 80%;
  margin-left: 2em;
}



/*This ends the less than 70em width screen size*/

@media screen and (min-width: 35em) {

.fa-bars{
  display: none;
}

/*This are the changes to the header*/
.hero h1 {
          width: 30%;
          font-size: 1em;
          padding: 3em;
        }

header ul{
          list-style-type: none;
          display: flex;
          flex-direction: row;
          justify-content: flex-end;
        }

header ul li{
            flex: 0 0 3%;
        }
        /*This is the chnge to the header*/

/*BODY Changes*/

/* Body around Articles and Sections */
.container{
  width: 100%;
  display: inline-block;

  /*Remove:
  Display:flex;
  flex-direction:row;
  */
          }

  section main{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    height: 100%;
    width: 80%;
    justify-content: space-around;
    align-items:center;
              }

  .posts {
          /* DO NOT CHANGE THESE */
          color: #444444;
          margin: auto;
        }

        /* Indiviudal ARTICLEs 1-6 */
  section main article{
    flex: 0 0 45%;
    margin: 2%;
    width: 70%
                      }

  .posts article {

            /* DO NOT CHANGE THESE */
            background-color: #dddddd;
            border: 1px solid #444444;
            height: 10em; /* this is just so we can see the articles since they have no content */
          }

  /* SIDEBAR GROUP 1-3 */
  aside{
    display: flex;
    flex-direction: row;
    flex: 0 0 25%;
    height: 100%;
    justify-content: space-around;
        }


  .sidebar {

      /* DO NOT CHANGE THESE */
      background-color: #aaaaaa;
      color: #444444;
            }


  .sidebar section {
      /* DO NOT CHANGE THESE */
      background-color: #dddddd;
      border: 1px solid #444444;
      height: 10em; /* this is just so we can see the articles since they have no content */
      margin-top: 1em;
      width: 25%;
                  }

  /* Indiviudal Sidebars 1-3 */
  aside section{
    margin-bottom: 1em;
                }

/*BODY Changes*/



/*Footer Changes*/

footer{
  border: 1px solid rgb(0, 0, 255);
  width: 100%;
  display: flex;
  justify-content: flex-start;
  border-radius: 0 0 1em 1em;
      }
footer nav{
  width: 50%;
          }

p{
  width: 50%;
  font-size: 80%;
  }
/*Footer Changes*/

}

@media screen and (min-width: 70em) {
  body {

      /* DO NOT CHANGE THESE */
      font-family: Verdana, Arial, sans-serif;
  }

  footer {

      /* DO NOT CHANGE THESE */
      background-color: #444444;
      color: #eeeeee;
    }

  header{
  width: 100%;
  border-radius: 1em 1em 0 0;
  }

  .hero {
      /* DO NOT CHANGE THESE */
      background-color: #444444;
    }

  .hero h1 {
        /* DO NOT CHANGE THESE */
        color: #ffffff;
        width: 30%;
        font-size: 1em;
        padding: 3em;
      }

  header ul{
    list-style-type: none;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    flex: 0 0 10%;
    margin-bottom: 0;


  }

  header ul li{
      flex: 0 0 7%;
      margin-left: 1em;
      padding: .5em;
  }

  section{
  display: flex;


  }

  /* Body around Articles and Sections */
  .container{
    width: 92%;
    display: flex;

  }

  /* Group of ARTICLEs 1-6 */
  section main{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    height: 100%;
    width: 80%;
    justify-content: space-around;
    align-items:center;
  }
  .posts {
          /* DO NOT CHANGE THESE */
          color: #444444;
        }

        /* Indiviudal ARTICLEs 1-6 */
  section main article{
    flex: 0 0 45%;
    margin: 2%;
    width: 70%
  }
  .posts article {

            /* DO NOT CHANGE THESE */
            background-color: #dddddd;
            border: 1px solid #444444;
            height: 10em; /* this is just so we can see the articles since they have no content */
        }

  /* SIDEBAR GROUP 1-3 */
  aside{
    display: flex;
    flex-direction: column;
    flex: 0 0 25%;
    height: 100%;
    padding-left: 1em;
    padding-right: 1em;
  }
  .sidebar {

      /* DO NOT CHANGE THESE */
      background-color: #aaaaaa;
      color: #444444;
  }
  .sidebar section {
      /* DO NOT CHANGE THESE */
      background-color: #dddddd;
      border: 1px solid #444444;
      height: 10em; /* this is just so we can see the articles since they have no content */
      margin-top: 1em;
      width: 100%;
  }

  /* Indiviudal Sidebars 1-3 */
  aside section{
    margin-bottom: 1em;

  }






  footer{
    border: 1px solid rgb(0, 0, 255);
    width: 100%;
    display: flex;
    justify-content: flex-start;
    border-radius: 0 0 1em 1em;
  }
  footer nav{
    width: 50%;
  }

  p{
    width: 50%;
    font-size: 80%;
  }


}
