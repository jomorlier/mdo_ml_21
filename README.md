# mdo_ml_21
Repo for MULTIDISCIPLINARY OPTIMIZATION AND MACHINE LEARNING FOR ENGINEERING DESIGN INTERNATIONAL VIRTUAL COURSE

https://mdoml2021.ftmd.itb.ac.id

This 2 hours course untitled "Design for Additive Manufacturing: Topology Optimization" is divided into 4 parts
## Lessons
Part1 The Big Picture for today and Sensitivities Analysis  20’
[PDF](https://github.com/jomorlier/mdo_ml_21/blob/main/mdo_ml_part1_compressed.pdf)

Part2 Theoretical Background On SIMP 30’
[PDF](https://github.com/jomorlier/mdo_ml_21/blob/main/mdo_ml_part2_compressed.pdf)

Part3 3D Printing 15’
[PDF](https://github.com/jomorlier/mdo_ml_21/blob/main/mdo_ml_part3_compressed.pdf)

Part4  Ecoptimization & Computational Fabrication 35’
[PDF](https://github.com/jomorlier/mdo_ml_21/blob/main/mdo_ml_part4-compressed.pdf)

## link to codes
[top88](https://www.topopt.mek.dtu.dk/apps-and-software)

[top3D](https://www.top3d.app)

[topGGP](https://github.com/topggp/blog)

[EMTO](https://github.com/mid2SUPAERO/EMTO)

[SMT](https://github.com/SMTorg/smt) and the [documentation](https://smt.readthedocs.io/en/latest/)


## Tutorials

Estimate derivatives by simply passing in a complex number to your function.
A single (complex) function evaluations computes both the function's value **(Re)** and the derivative **(Im)**.
Is it **always** possible to do this? I mean with a standard code form industry (Nastran, Fluent etc...)?
[Complex-step derivatives](http://htmlpreview.github.io/?https://github.com/jomorlier/mdocourse/blob/master/ComplexStep/ComplexStep.html)

Comparison of **Symbolic/Finite Differences/DIRECT/ADJOINT Method** on a really simple mechanical system (2DOFs).
Play with the code for **checking** Symbolic with Finite Differences. Play with $\Delta_x$ ?
By the way, just add the complex step approach, not so difficult when you have access to the **original** code.
Oh, at the end which method is exact? 
[gradient evaluation](http://htmlpreview.github.io/?https://github.com/jomorlier/mdocourse/blob/master/Sensibility/sensitivity_TD.html)

BTW, How Nastran is doing for gradient computation on SOL2OO ?
[gradient nastran](https://app.amanote.com/note-taking/document/827200fd-e137-475b-aab5-58d734086654)

For people who are not familliar with Finite Element Method:
http://designinformaticslab.github.io/mechdesign_lecture/2018/01/28/featop.html

On using top88 to solve a 3pt bending problem:
[The 3 point bending projected corrected using top88](http://htmlpreview.github.io/?https://github.com/jomorlier/ALMcourse/blob/master/top88/topopt_3ptBENDING.html)

Stress based TopOpt in 2 parts:
Part A:  [Constraints Agreggation](http://htmlpreview.github.io/?https://github.com/jomorlier/mdocourse/blob/master/AdvancedTopOpt/ConstraintsAgreggation.html)
Thanks to my PhD Simone.

Part B:  [Stress Based TopOpt](http://htmlpreview.github.io/?https://github.com/jomorlier/mdocourse/blob/master/AdvancedTopOpt/StressBasedTopOpt.html)
Thanks **AGAIN** to my PhD Simone.
Before you can use Method of Moving Asymptotes (MMA) as an optimizer in our stress based topology optimization program, you need to obtain the Matlab implementation of MMA from Prof. Krister Svanberg (krille@math.kth.se) from KTH in Stockholm Sweden.

## Prof's courses

https://github.com/jomorlier/mdocourse

https://github.com/jomorlier/feacourse

https://github.com/jomorlier/almcourse

https://github.com/jomorlier/OptimizationCourse
