
Design method etc


### Language Basics

```scheme
; some expressions
(+ 3 4);
(+ 3 (* 4 2));
(/ 400 4);

; math
(sqr 3);
(sqrt 16);

(sqrt (+ (sqr 3) (sqr 4)) );

; join strings
(string-append "steve" " " "davies");

; cut out a substring
(substring "falafel" 2 5);

; constants

(define SOME_THING 5000)


```

### Images

```scheme
(require 2htdp/image)

(circle 10 "solid" "blue")
(rectangle 50 100 "solid", "red")

(above (text "hello" 24 "orange")
       (text "hello" 20 "blue")
       (text "hello" 16 "yellow"))

(overlay (circle 16 "solid" "orange")
       (circle 20 "solid" "green")
       (circle 24 "solid" "yellow"))

```

#### Functions

```scheme
; function definitions
(define (bloop x)
  (circle 20 "solid" x))

(bloop "blue")
(bloop "pink")
(bloop "orange")
```

