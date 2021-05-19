
___
## 1. neural networks
1) 뉴럴넷은 인간의 뉴런에서 영감을 받아 만들어졌다. 뉴런은 만약 충분한 크기의 자극을 받으면 그들은 가지를 따라 다른 뉴런들을 자극시킨다. 
![1](https://user-images.githubusercontent.com/63699718/118811382-e7bfe080-b8e7-11eb-96da-595bf6a08a6f.PNG)
2)  이걸 수학적으로 간단한 함수로 퍼셉트론이라 한다. 인간의 뉴런처럼 충분한 자극을 받으면 자극을 주고 그게 아니라면 자극을 주지 않는다. 여기서 자극을 주는 한계점을 정하는 것이 activation function이다. 
![2](https://user-images.githubusercontent.com/63699718/118811659-39686b00-b8e8-11eb-96f3-61aa65365f06.PNG)
3) activation function에는 여러개가 있고 그중 몇가지가 sigmoiod function, hyperbolic tangent, rectified linear unit(ReLU) 이다.
![3](https://user-images.githubusercontent.com/63699718/118837696-0c27b700-b900-11eb-9d3c-5e141796f5c7.PNG)
sigmoid의 경우 어떠한 분수가 들어가도 0과1의 두가지 경우만 나온다. ReLU의 경우는 0초과의 값을 넣으면 모두 1이 나오고 아니면 0이 나오는 것이다.
## 2. universality
universal approximation이란 1개의 히든 레이어를 가진 Neural Network를 이용해 어떠한 함수든 근사시킬 수 있다는 이론을 말한다.
## 3. learning problems
## 4. gradient descent
## 5. empirical risk minimization and loss functions
## 6. back propagation and automatic differentiation.
## 7. architectural consideration