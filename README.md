
public class TestMethod {
	
	A a = new A();
	
	public class A{
		

		public	class B{
			
			public	class C{
				
				public void c(int a){
					System.out.println(a);
				}
			}
			
			public C b(){
				C c = new C();
				
				System.out.println("b");
				
				return c;
			}
		}
		
		
		
		
		public B a(){
			B b = new B();
			
			System.out.println("a");
			return b;
		}
	}

	public static void main(String[] args) {
		// TODO Auto-generated method
		TestMethod tm = new TestMethod();
		int a= 0;
			tm.a.a().b().c(++a);
	}

}
