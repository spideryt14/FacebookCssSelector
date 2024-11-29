# FacebookCssSelector
Automation
package com.fb;
import org.openqa.selenium.By; 
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import java.util.Scanner;



public class Taleban {

	public static void main(String[] args) throws InterruptedException 
	{
		WebDriver mortua=new ChromeDriver();
		mortua.get("https://www.facebook.com/");
		mortua.findElement(By.cssSelector("input.inputtext")).sendKeys("asdfjkli288@gmail.com");
		mortua.findElement(By.cssSelector("input.inputtext")).clear();
		
		mortua.findElement(By.cssSelector("input.inputtext")).sendKeys("asdfjkl288@gmail.com");
		mortua.findElement(By.cssSelector("input#pass")).sendKeys("osmandembele");
		mortua.findElement(By.name("login")).click();	
		Thread.sleep(10000);
		mortua.findElement(By.name("tryanotherway")).click();
		Thread.sleep(3000);
		mortua.findElement(By.name("reset_action")).click();
		mortua.findElement(By.cssSelector("input[type='text']")).sendKeys("xyzabc56@gmail.com");
		mortua.findElement(By.cssSelector("button[type='submit']")).click();
		mortua.close();
		
		
		
	}

}
