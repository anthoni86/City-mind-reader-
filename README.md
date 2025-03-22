# City-mind-reader-
A fun mind-reading city guessing game where the computer predicts the city you're thinking of!


# City Mind Reader Game  

## Overview  
The **City Mind Reader Game** is an interactive web game where the computer guesses a city that the player is thinking of. The game works by asking a **single question**, and based on the player's response, it identifies the city.  

## How It Works  
1. The game displays a **list of 10 cities** in a structured table.  
2. The player thinks of a city from the list.  
3. The game asks a **single question**, showing checkboxes corresponding to columns in the table.  
4. The player selects the columns where their city appears.  
5. Upon submission, the game **reveals the guessed city** with special effects.  

## Features  
- **Minimal animation** for better user engagement.  
- **Fixed table layout** displaying all cities for better visibility.  
- **Unique text styles** for each city.  
- **Flashing effect & flower splash animation** when the city is revealed.  
- **Developer name at the bottom with continuous animation.**  
- **No timer** to keep the game relaxed and enjoyable.  

## Game Logic  
- The cities are arranged into **four columns**.  
- The user selects the columns where their city appears.  
- Using a predefined pattern, the game determines the correct city.  

### Example City Arrangement  

| City Name  | Column 1 | Column 2 | Column 3 | Column 4 |  
|------------|---------|---------|---------|---------|  
| Delhi      | ✓       |         | ✓       |         |  
| Chennai    |         |         | ✓       | ✓       |  
| Kolkata    | ✓       |         | ✓       | ✓       |  
| Mumbai     |         | ✓       | ✓       | ✓       |  
| Shanghai   | ✓       | ✓       | ✓       | ✓       |  
| Singapore  |         |         |         |         |  
| New Jersey |         | ✓       |         |         |  
| Chicago    |         |         | ✓       |         |  
| London     |         |         |         | ✓       |  
| Hong Kong  |         | ✓       |         |         |  



