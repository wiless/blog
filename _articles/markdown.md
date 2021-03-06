---
layout: article
draft: false
summary: Sample markdown file with all features
index: -1
--- 

# Testing markdown renderer


## TOC This works, Lets look at 
- [chapter 2](#chapter-2)
- [chapter 3](#chapter-3)

Test your markdown content here.. 
<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    A-->D;
</div>

You can use foot notes [^1] like this. 


<div class="mermaid">
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!

</div>


<div class="mermaid">
gantt
       dateFormat  YYYY-MM-DD
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48h
</div>

```go
func Name(str string){
return x;
}
```
<div class="mermaid">
journey
    title ITU Timeline
    section Development
      Make tea: 5: 3GPP
      Go upstairs: 3: TSDSI
      Do work: 1: Me, Cat
    section Evaluation
      Go downstairs: 5: Me
      Sit down: 5: Me
</div>

This should be well quoted ..

> this is simple quote


## Step 2
 
*  a 
* b
* c

----





# Chapter 2
 


[^1] - I am a footnote you can return back ...