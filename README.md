test# Truthiness Code Challenge

## Objectives

1. Strengthen your understanding of truthiness in Ruby
2. Practice using boolean and comparison operators

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge I</h1></div><div class='question-block'><p class='question-title'><p>Take a look at the code below. We have defined a method, <code>returning_true</code> that uses a comparison operator, the <code>&lt;</code> (less than) to compare the number 14 to...nothing. Fill out the necessary portion of the code so that the method will return <code>true</code>. Then, call the method.</p>
</p><div class='repl-answer-block'><textarea data-initial='def returning_true
	14 < #your solution here
end

# DO NOT touch the following line!

returning_true' data-solution='["def returning_true","\t14 < 20","end","returning_true"]' data-validation='["assert_true(response)"]' data-language='ruby' id='repl-0' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challanege II</h1></div><div class='question-block'><p class='question-title'><p>Here we have a method, <code>returning_false</code> that uses both comparison and boolean operators. Fill out the remainder of the method so that it returns false. Then, call the method.</p>
</p><div class='repl-answer-block'><textarea data-initial='def returning_false
	7 > 4 && 100 < #your solution here
end

#DO NOT touch the following line!

returning_false' data-solution='["def returning_false","\t7 > 4 && 100 < 99","end","returning_false"]' data-validation='["assert_false(response)"]' data-language='ruby' id='repl-1' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge III</h1></div><div class='question-block'><p class='question-title'><p>Take a look at the method <code>using_truthiness</code> below. Fill out the missing portion so that the method returns false. Then, call the method.</p>
</p><div class='repl-answer-block'><textarea data-initial='def using_truthiness
	7 > 8 || #your solution here
end

#Do NOT touch the following line!

using_truthiness' data-solution='["def using_truthiness","\t7 > 8 || 8 < 7","end","using_truthiness"]' data-validation='["assert_equal(response, false)"]' data-language='ruby' id='repl-2' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>




