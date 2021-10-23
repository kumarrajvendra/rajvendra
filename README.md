# rajvendra
importing code
package com.been;

public class Employee {
	
	private int sno;
	private String name;
	
	
	
	
	public Employee() {
		
	}
	public void setSno(int sno) {
		this.sno = sno;
	}
	public void setName(String name) {
		this.name = name;
	}
	@Override
	public String toString() {
		return "Employee [sno=" + sno + ", name=" + name + "]";
	}
	
	
	
}
