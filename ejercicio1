%% Calculo del limite
n=[1 10 100 500 1000 2000 4000 8000];
y=(1+(1./n)).^n

%% Creación de matriz diagonal
A=[2 6; 3 9];
B=[1 2; 3 4];
C=[-5 5; 5 3];
G=zeros(6);
G(1:2,1:2)=A;
G(3:4,3:4)=B;
G(5:6,5:6)=C;
G

%% Problema de la serie de Fibonnacci y la razon aurea
f=zeros(1,50);
a=zeros(1,50);
f(1)=1;
f(2)=1;
a(1)=1;
for k=3:50
f(k)=f(k-2)+f(k-1);
a(k)=f(k)/f(k-1);
end

%% Representacion de funciones
x1=-10:1:-5;
fx1=(2+sin(x1));
plot(x1,fx1,'r:o')
hold on
x2=-4.99:1:1.99;
fx2=exp(x2);
plot(x2,fx2,'b-*')
hold on
x3=2:1:10;
fx3=log(x3.^2 + 1);
plot(x3,fx3,'.-')

%% Solucion de Ecuaciones
r=10;
solucion
