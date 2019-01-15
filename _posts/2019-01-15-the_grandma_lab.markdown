---
layout: post
title:      "The Grandma Lab"
date:       2019-01-15 07:01:55 +0000
permalink:  the_grandma_lab
---


Coming back to Ruby, I thought it was fun to experiment with 3 different methods for this lab.

Method 1
def speak_to_grandma(sentence)
  if sentence == "I LOVE YOU GRANDMA!"
    return "I LOVE YOU TOO PUMPKIN!"
  elsif sentence == "Hi!"
    return "HUH?! SPEAK UP, SONNY!"
  elsif sentence == "Hi Nana, how are you?"
    return "HUH?! SPEAK UP, SONNY!"
  elsif sentence == "WHAT DID YOU EAT TODAY?"
    return "NO, NOT SINCE 1938!"
  elsif sentence == "WHAT?"
    return "NO, NOT SINCE 1938!"
  else sentence == "I LOVE YOU GRANDMA!"
    return "I LOVE YOU TOO PUMPKIN!"
  end
end
 
Method 2
def speak_to_grandma(phrase)
  if phrase == "I LOVE YOU GRANDMA!"
    return "I LOVE YOU TOO PUMPKIN!"
  elsif phrase == phrase.upcase
    return "NO, NOT SINCE 1938!"
  else
    return "HUH?! SPEAK UP, SONNY!"
  end
end
 
Method 3
def speak_to_grandma(phrase)
  if phrase == "I LOVE YOU GRANDMA!"
    return "I LOVE YOU TOO PUMPKIN!"
  elsif phrase == “#{phrase}”.upcase
    return "NO, NOT SINCE 1938!"
  else
    return "HUH?! SPEAK UP, SONNY!"
  end
end

