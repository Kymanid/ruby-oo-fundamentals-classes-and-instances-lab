# Ex.

north_west = Baby.new
north_west.cry # instance method

Baby.cry # Class method 

class Baby
    def initialize # Hook / Callback - because it is a method
        cry 
    end
end

def cry  # instance method - represents and object ability to have logic
    puts "Waaaaaa!!!"
    end
end


Baby.new 
=> Waaaaaaaa!!!

# to call it, you can put for example  whatever_name = Baby.new
# next step to call it / whatever.cry
# => Waaaaaaa!!!


north_west.name = "North West"
# if this is placed in irb / this will comeback a error sicne "name" hasn't been defined

def name=(the_baby_name) # Writer
    @my_name = the_baby_name 
    # take the value of "the_baby_name" and put it the variable "my_name"
end

def name # Reader
    @my_name # my_name is a "Local Variable" / casting the scope of the variable with "@"
end
end


@instance Variable