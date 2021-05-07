<h1>Prefix and Suffix Search</h1>
<p><br>
Design a special dictionary which has some words and allows you to search the words in it by a prefix and a suffix.<br>
Implement the WordFilter class:<br>
&emsp;&emsp;•	WordFilter(string[] words) Initializes the object with the words in the dictionary.<br>
&emsp;&emsp;•	f(string prefix, string suffix) Returns the index of the word in the dictionary which has the prefix prefix and the suffix suffix. If there is more &emsp;&emsp;&emsp;than one valid index, return the largest of them. If there is no such word in the dictionary, return -1.<br>
<br> 
Example 1:<br>
&emsp;&emsp;Input<br>
&emsp;&emsp;&emsp;&emsp;["WordFilter", "f"]<br>
&emsp;&emsp;&emsp;&emsp;[[["apple"]], ["a", "e"]]<br>
&emsp;&emsp;Output<br>
&emsp;&emsp;&emsp;&emsp;[null, 0]<br>
<br>
&emsp;&emsp;Explanation<br>
&emsp;&emsp;&emsp;&emsp;WordFilter wordFilter = new WordFilter(["apple"]);<br>
&emsp;&emsp;&emsp;&emsp;wordFilter.f("a", "e"); // return 0, because the word at index 0 has prefix = "a" and suffix = 'e".<br>
<br>
Constraints:<br>
&emsp;&emsp;•	1 <= words.length <= 15000<br>
&emsp;&emsp;•	1 <= words[i].length <= 10<br>
&emsp;&emsp;•	1 <= prefix.length, suffix.length <= 10<br>
&emsp;&emsp;•	words[i], prefix and suffix consist of lower-case English letters only.<br>
&emsp;&emsp;•	At most 15000 calls will be made to the function f.<br>
<br></p>

