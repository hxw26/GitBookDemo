### "quiz" plugin can be used for designing multiple choice questions
<quiz name="Quiz 1">
<question>
<p> Q1. The Nyquist theorem for sampling 

 1) Relates the conditions in time domain and frequency domain
 2) Helps in quantization
 3) Limits the bandwidth requirement
 4) Gives the spectrum of the signal</p>

<answer>a. 1, 2 and 3 are correct</answer>
<answer>b. 1 and 2 are correct</answer>
<answer correct>c. 1 and 3 are correct</answer>
<answer>d. All the four are correct</answer>
<explanation>Nyquist theroem specify the minimal bandwidth to sample a continue signal in time domain to a digital signal.</explanation>
    </question>
</quiz>

---
### "excercise" plugine can be used for answering a short question.It is failed due to an error after clicking Submit
{% exercise %}
What should be the sampling rate for a 10Hz signal

{% initial %}
Sampling Rate =

{% solution %}
Sampling Rate = 20;

{% validation %}
assert(x == 20);

{% context %}
// This is context code available everywhere
// The user will be able to evaluate `exposedVar`
var exposedVar = 3;
// ... or call `exposedFunction`
function exposedFunction {
    return 3;
}
{% endexercise %}

---
### "Fill-in-blank" plugine can be used for filling balnks. It is failed as the double $ sympol has a conflict with GitBook

{%fbq%}Testing. Please type hello $(hello)## and $$world ## (world).{%endfbq%}



