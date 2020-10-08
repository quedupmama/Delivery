public class Delivery {
private	String address; 
private	String phoneNumber;
	public Delivery (String address, String phoneNumber) {
		this.address = address;
		this.phoneNumber = phoneNumber;
			
	}
public String getAddress() {
	return this.address; 
}
public void setAddress(String address ) {
	this.address = address;
  
  Delivery deliveryOne = new Delivery ("3358 Jackson St", "4047779311");
System.out.println(deliveryOne.getAddress()); 
deliveryOne.setAddress("1313 Mockingbird");
System.out.println(deliveryOne.getAddress());
	}
