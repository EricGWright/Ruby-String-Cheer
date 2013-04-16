#Ruby exercise to parse a string of text

system ("cls")
puts "Yo! Who dis?"
name = gets.downcase.chomp!
system ("cls")
name.split("").each do |i|
  if 'aefhilmnorsx'.include? i
    puts "Give me an #{i.chr.upcase}..."
  else
    puts "Give me a  #{i.chr.upcase}..."
  end
end
puts ""
puts "#{name.capitalize}! #{name.capitalize}! YAY #{name.upcase}!"
puts ""
