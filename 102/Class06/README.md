Java & java Script are different
— JavaScript is not "Interpreted Java". Both "Java" and "JavaScript" are trademarks but different lang and syntax.

write JS in < script> opening tag and </script > closing tag.

To interact with JS we will use the "alert"
function eventhough their are many functions to use.

< script language="javascript">

alert("Hello World");

</ script>

**prompt** will show up as a pop up window with the text that is provided. The prompt will ask a question with an yes or no answer.  
< script>

var name = prompt("Your name:", "");
document.write("Hello ", name);

< /script >

> In order to make sense of your prompt you will have to have an "if statement" an if statement is the result of a yes or no answer.

< script >

if (confirm("Shall I say Hello World?" )) {
document.write( "Hello World" );
} else {
document . write ("OK, I won't say it.");
}

</ script>
