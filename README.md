# grumpy
Very pessimistic statistical testing and modelling

```
p1<-35
p2<-42
b<-p2-p1

true_p1<-37
true_p2<-40

a<-true_p2-true_p1


p1_m<-40
p1_f<-2*true_p1-p1_m
p2_m<-35
p2_f<-2*true_p2-p2_m

p<-0.45

(p*p2_m+(1-p)*p2_f)-(p*p1_m+(1-p)*p1_f)
```
