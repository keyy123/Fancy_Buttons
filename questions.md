What does rem mean? 
3:46/1:10:25

What does padding: 6px 12px mean for an element?
3:50/1:10:25

What is -moz/-webkit-box-shadow: inset 0 1px 0 0 #4d73bf; do? Why do we need 3 of the same/similar CSS props?
4:26

What does inset value do for box-shadow css prop?
6:25

How to read the values within a box-shadow css prop?
6:44 - 7:52

What is text-shadow css prop? How to read it?
8:26 

How should you add CSS rules in stylesheet when they address another state of the element like hover (LVHA)? Why?

8:55 - 9:30

Why are we using postion: relative on a button?
12:35 

What is the difference between em and rem units?
13:00 - 13:11

What does the following CSS property mean in plain english: 

box-shadow: -6px 6px 0 hsl(16, 100%, 30%);


What is outline CSS prop?

How do we use top and left in CSS? 

We have a parent element (even same element) that has position: relative set on it. This sets the element somewhere in document flow and now we can use CSS props to move the element relative from the parent element's position like top, left, bottom, and right. 

14:30 - 14: 45


Explain the significant CSS properties within the following code below as simply as possible. What is it trying to achieve? :

.btn-3d-1 {
    position: relative;
    background: orangered;
    border: none;
    color: white;
    padding: 15px 24px;
    font-size: 1.4rem;
    box-shadow: -6px 6px 0 hsl(16, 100%, 30%);
    outline: none;
}

    .btn-3d-1:hover {
        background: hsl(16, 100%, 45%);
    }

    .btn-3d-1:active {
        background: hsl(16, 100%, 40%);
        top: 3px;
        left: -3px;
        box-shadow: -3px 3px 0 hsl(16, 100%, 30%);
    }

How do we connect the button to its box-shadow to make a 3d button?
18:00 - 18:15;

We need to make a shape to connect the box-shadow and button on forefront. In this case, a triangle. We can do this by making a absolutely positioned border with no width or height with a border that is transparent on all 4 sides with a size but only on one side have a solid with size and a color to make a shape then move it. 

What is ::before CSS prop? 
16:10 - 16:25

Why do we need to use content css prop for psuedo elements ::before and ::after?
16:32 - 16:40

Why do we use border-left-width: 0 or border-bottom-width: 0? 
18:30 - 18:50
20:30 - 22:20

How to style the psuedo element of a state of an element in CSS? (example: div:active::before/after)?

23:20

HOw do we fix the triangles in the active state?
23:30 - 24:20

Why do we use z-index? 

How to stack multiple box-shadows on a single element?
30:00 - 31:00

When we click the button with top: 2px in active state why does it go down?
33:50 - 34:55

How to add a gradient to a border in CSS?
37:30 - 38:30

How to fix the gradients so they are not on the corners of the border? What does border-image-slice does? 
38:30 - 39:20

How to use transition in CSS?
39:35 - 39:55

