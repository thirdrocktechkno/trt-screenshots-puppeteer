# My project's README

1) Install dependencies using below command in terminal 

	npm install

2) Update URLs and dimensions in 'getScreenShots.js' as per your requirments
	
	Ex: change in Below array for update URLs

		const urls = [
		    { name: 'Home', url: 'https://www.thirdrocktechkno.com/' }, 
		    { name: 'About', url: 'https://www.thirdrocktechkno.com/about-us' }
		   
		];

	Name represent the name or title of page. Like Home, About, Contact.
	Link respresent URL of page of which tou want to test.

	     Change in devices array for update or remove device
	
		const devices = [
		    { name: 'Highest', width: 1920, height: 1080 },
		    { name: 'Laptop-1', width: 1366, height: 768 }
		   
		];

	Name represnt name of device. ex - laptop, desktop, ipad
	Width represent width of that particular device.
	Height represent height of that particular device.
		
3) Then Run below command for get Screenshots in your screenshots directory
	
	node getScreenShots.js
