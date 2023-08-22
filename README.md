# OverriddingSample
![image](https://github.com/Brindasiva/OverriddingSample/assets/124075213/56eaa865-d8ca-4c70-9fb2-749fe1232612)

Run() method is implemented in both vehicle and car class.
When it comes to Run method in Car class, the complier will be confused which method to run as it also derives Run method from parent class Vechile.So to explicitly tell compiler to pick Car class method, we are using Override keyword.

