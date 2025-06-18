


<div id="testpuzzle2-sortableTrash" class="sortable-code"></div> 
<div id="testpuzzle2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="testpuzzle2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="testpuzzle2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "public class text {\n" +
    "	public static void main(String[] args){\n" +
    "    	System.out.println(&quot;Text eines Programms.&quot;);\n" +
    "    }\n" +
    "}\n" +
    "public static void main (String[&quot;Text eines Programms.]) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "testpuzzle2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "testpuzzle2-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#testpuzzle2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#testpuzzle2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
