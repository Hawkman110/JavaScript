function Geymflaug(name, life) 
{ 
		this.name = name; this.life = life; 
    
}

Geymflaug.prototype.showName = function() 
{ 

		alert("Nafn geymflaugar er " + this.name); 

};

geymflaug1 = new Geymflaug("SpaceRacer", 10); 
geymflaug2 = new Geymflaug("SpaceRacer", 10); 
geymflaug3 = new Geymflaug("LateRacer", 10);

geymflaug3.showName();

Geymflaug.prototype.fly = function() 
{ 

		this.speed = 5 + 1; 

};

geymflaug4 = new Gaymflaug("SpaceRacer", 10);

gaymflaug4.prototype.damage = function() 
{ 
		this.damage = life - 1; 
    
};
