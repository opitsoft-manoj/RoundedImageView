For Gradle 

allprojects {

		repositories {
		
			...
			maven { url 'https://jitpack.io' }
			
		}
		
	}
	
  
  dependencies {
  
	        implementation 'com.github.opitsoft-manoj:RoundedImageView:1.0.0'
		
	}




For Maven 


<repositories>
	
		<repository>
		
		    <id>jitpack.io</id>
		    
		    <url>https://jitpack.io</url>
		    
		</repository>
		
	</repositories>



<dependency>
	    <groupId>com.github.opitsoft-manoj</groupId>
	
	    <artifactId>RoundedImageView</artifactId>
	    
	    <version>Tag</version>
	    
	</dependency>
  
  
  
  
 
 We can use for create rounded image and cricle image 
  
  
   <com.mk.roundedimageview.RoundedImageView
       
        android:id="@+id/img"
	
        android:layout_width="100dp"
	
        android:layout_height="100dp"
	
        android:src="@mipmap/img_demo"
	
        app:roudedSize="50dp" />
        
        
        
    Mathods 
    
    roundedImageView.setCornerRadius(50);
    
        
        
        
        
        
        
