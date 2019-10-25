
# Toward a Definition of the Code Poet

> Originally published at https://ict.senecacollege.ca/~david.humphrey/writing/CodePoet.html
> (2001) My attempt to link Poetry and Programming, and define the central idea behind the Code Poets group.

When I say "Code Poet," what do you picture? Do you see a twenty-something dressed in a black turtleneck standing on a makeshift stage at the front of a café reading his latest Perl script? Do you envision a wizened professor smoking a pipe and stroking his beard while his foot quietly taps out the rhythms of the Linux kernel source? Or do you imagine a swooning couple whispering C couplets in one another's ear, lost in a moment of undulating bliss? Are any of these right? Are they all wrong? Just what is a Code Poet?

Instead of keeping you in eager anticipation for the remainder of this essay, I am going to begin with my conclusion up front: the term "Code Poet" is currently undefined. That's not quite the same as saying that there is no such thing as a Code Poet. What I am saying instead is that we haven't spent enough time considering the role of the programmer as poet. We've had time to develop no fewer than 150 separate programming languages, write and rewrite countless editors, compilers, debuggers, and other programming paraphernalia, and bury generations to come in billions of lines of unmaintainable code. We've even found ways to get machines to communicate with one another through thin air. A programmer is a scientist. A programmer is a business person. A program is an architect. But, "a programmer is a poet," that we haven't come to terms with yet.

Perhaps before we can give shape to the Code Poet, we should attempt to establish his/her existence. And to do this I want to draw your attention for a moment to the word Poet. What can we say about the poet, generally? Well, one good place to start is with the Greek origins of the word. In Greek a poetes is a maker, a creator, and by extension, an author. So that's the root etymology, but what about the word as we've come to know it in English? According to the Oxford English Dictionary, a Poet is someone who is "a writer in verse--distinguished by special imaginative or creative power, insight, sensibility, and faculty of expression." From this we can say that a poet is someone who is able to express ideas with a creativity and imaginative power such that ordinary language is transformed into something extraordinary. Notice that a poet is someone who uses "verse;" not English verse or German verse or Chinese verse, just verse. I believe that this distinction is particularly important because it means that poetry is something set apart from a specific language, what theorists might call a general rather than the particular idea.

If we agree that a poet is someone who uses or exploits language in order to express ideas in a creative way, we are half-way toward establishing the existence of the Code Poet. Let's call him/her a programmer, and ask the question, "what does a programmer do?" A programmer, we might say, writes programs that are run on a computer. These programs are written in languages like C, Java, Perl, Eiffel, Prolog, or Scheme and end-up getting translated, or compiled into instructions for a computer to follow. Many people I know in the literary community have told me that computer languages are not really languages because they are meant for computers, not humans. On the surface this argument seems solid: we programmers write in obscure "languages" that no one speaks, and before our "writings" can even be understood by the computer they must be compiled. Notice that word compiled. It turns out that the computer cannot understand our programming languages either. To a computer there is no difference between a C program, a telephone directory, and Shakespeare's play Hamlet. They are all just so many words and numbers.

Beginning with Assembly and Fortran, programming languages allowed humans to express ideas separate from the machinery that would carry out their instructions. Despite what luddites will tell you about "computer people," programmers don't think like machines. Programmers use machines to express ideas, human ideas. A computer program is not a one-to-one mapping of man and machine. There are countless ways to do the same thing in programming languages, just as there are countless ways to express the same idea in natural languages.

Strangely, there are as many programmers as there are technophobes who will have a hard time with what I'm proposing. Many programmers don't believe in the humanity of programming languages either. They call it code in an effort to make it inaccessible to the average person. I won't argue with that, it is inaccessible. And in this sense our initial depictions of the Code Poet reading his/her work in front of a crowd are just plain silly. However, that doesn't change the fact that the only one capable of understanding what a programmer writes is another programmer, not a computer. If we accept this, and we must, it follows that we need to explore what programmers are saying to each other, and how they are saying it. Just as everything we write in English is not a poem, not every C program is a Code Poem either. So what makes a Code Poem then?

No discussion of computer programming would be complete without a few examples, so let's look at some code in an effort to define the Code Poem. I'll begin in the canonical "Hello World" style, and present a short C program of the type a student in his/her first programming course might write.

```
#include <stdio.h>

void main(void) {
    printf("SOME say the world will end in fire,\n");
    printf("Some say in ice.\n");
    printf("From what I've tasted of desire\n");
    printf("I hold with those who favor fire.\n");
    printf("But if it had to perish twice,\n");
    printf("I think I know enough of hate\n");
    printf("To know that for destruction ice\n");
    printf("Is also great\n");
    printf("And would suffice.\n\n");
}
```

It doesn't take a degree in computer science to see that this program will print-out the text to Robert Frost's poem "Fire and Ice". Is this a Code Poem? It certainly has both code and poetry. But is that all it takes to create a Code Poem? I would argue that it is not. Although it will compile, there is nothing in this program that distinguishes it as a good C program. What I mean by good here is that when I read it as a programmer, I am not challenged to rethink the way I write code, or to ponder some subtlety of the language (in this case C). When I read it my attention is instantly drawn to the output of the program. I can "compile" and run it in my head and see the result. If we call this program a Code Poem then we are guilty of believing that programming languages are nothing more than containers for meaning, or a scaffolds on which to build. Instead of being a Code Poem, this is a Poem in Code, a Poem and a Program, but nothing more.

Let's look at another example:

```
r-p-o-p-h-e-s-s-a-g-r
   who
a)s w(e loo)k
upnowgath
  PPEGORHRASS
        eringint(o-
aThe):l
 eA
     !p:
S         a
 (r
rIvInG .gRrEaPsPhOs)
    to
rea(be)rran(com)gi(e)ngly
,grasshopper;
```

Admittedly this is a much more difficult example. Here we have all the complexity that we lacked in our first example program. However, whether you are a luddite or a programmer, you may have noticed that this is not a computer program at all. This is a poem by E.E. Cummings about a grasshopper published in 1923. The language this time is English, not C. I have included this poem in order to demonstrate that poetry in any language can be difficult in the sense that it can push the language farther than it has been taken before. This poem doesn't bear much resemblance to a telephone list or to Hamlet. In fact, that's what makes it a poem. By stretching the possibilities of English further than they had been taken in the past, Cummings truly created something new by means of the machinery of language. As readers of the poem we both recognize, and don't, what's going on at the same time. Here's another example:

```
#!/usr/bin/perl
# 472-byte qrpff, Keith Winstein and Marc Horowitz <sipb-iap-dvd@mit.edu>
# MPEG 2 PS VOB file -> descrambled output on stdout.
# usage: perl -I <k1>:<k2>:<k3>:<k4>:<k5> qrpff
# where k1..k5 are the title key bytes in least to most-significant order

s''$/=\2048;while(<>){G=29;R=142;if((@a=unqT="C*",_)[20]&48){D=89;_=unqb24,qT,@
b=map{ord qB8,unqb8,qT,_^$a[--D]}@INC;s/...$/1$&/;Q=unqV,qb25,_;H=73;O=$b[4]<<9
|256|$b[3];Q=Q>>8^(P=(E=255)&(Q>>12^Q>>4^Q/8^Q))<<17,O=O>>8^(E&(F=(S=O>>14&7^O)
^S*8^S<<6))<<9,_=(map{U=_%16orE^=R^=110&(S=(unqT,"\xb\ntd\xbz\x14d")[_/16%8]);E
^=(72,@z=(64,72,G^=12*(U-2?0:S&17)),H^=_%64?12:0,@z)[_%8]}(16..271))[_]^((D>>=8
)+=P+(~F&E))for@a[128..$#a]}print+qT,@a}';s/[D-HO-U_]/\$$&/g;s/q/pack+/g;eval
```

So what is this? Poetry, programming, or the result of a thousand monkeys on a thousand keyboards? I can quickly rule out the third possibility. This is Keith Winstein's qrpff program written in Perl, which will decode DVDs (http://www-2.cs.cmu.edu/~dst/DeCSS/Gallery/qrpff.pl). Therefore, yes the second option is also true. But what about the first? Is this poetry? Keith Winstein wrote this program in order to present it in a seminar at MIT. He could have done it more efficiently in other languages (in fact others have), and more clearly. But he didn't, and that should interest us. The closer we get to answering why creative programmers do what they do in code, the closer we get to a definition of the Code Poet.

Throughout this essay I have been making the point that poetry is the imaginative expression of ideas in language. It's such an important point that I want to close on it. As a reader of English I am challenged by, and struggle with Cumming's poem'in fact I struggle with much of his work. It forces me to rethink what I know about English. To have words do things they don't usually do. As a programmer I am equally challenged by, and struggle with Winstein's qrpff. In his attempt to express something in such a minimal space, he too has pushed the boundaries of language. As a reader and a programmer I engage with languages in order to expand my understanding of the world around me, in order to uncover the beauty and order of the universe. I couldn't do without poetry, whether we're talking about the Cummings or the Winstein variety.

I said at the outset that the term "Code Poet" is undefined. This is still true. I believe that within every programmer and every program there is the potential for the Code Poet and Code Poem respectively. What the Code Poet does exactly will be defined in part by what I do as a programmer, in part by what you do as a programmer. I hope to read in your code the possibility of something previously unknown to me. I'm convinced it can happen, because it has already happened to me. As a reader I look forward to engaging your code poems for what they are: creative and imaginative expressions of what it means to be human.

`return (0);` 