# Iterator
## Iteratorパターンとは?
iterateという英単語は「繰り返す」という意味であり、iteratorは日本語にすると「反復子」などと呼ばれるもの  
Iterator パターンは、要素の集まりを保有するオブジェクトの各要素に順番にアクセスする方法を提供するためのパターンである  
集約オブジェクトとして List クラスとListオブジェクトが持つ要素にアクセスする方法を提供する「操作方法」クラスを独立させておく  
すると、必要な走査方法を与えるクラスをユーザが自分で作成し、 これを利用できるようになり、より柔軟な設計となる

class Student:  
  def __init__(self, name, sex):  
    self.name = name    
    self.sex = sex  
  
  def get_name():  
    return self.name  
  
  def get_sex():  
    return self.name  
  
