# Pokémon API Access Guide: Arceus, Charizard, Gengar

This guide shows how to access different types of data returned from the Pokémon API for three Pokémon: **Arceus**, **Charizard**, and **Gengar**.

---

##  **1. Arceus**

1. **Accessing a level 1 property (e.g., `name`, `weight`):**
    ```javascript
    console.log(response.name);   // "arceus"
    console.log(response.weight); // 3200
    ```

2. **Accessing an object within the response:**
    ```javascript
    console.log(response.sprites); // Object with image URLs
    ```

3. **Accessing a specific key in the object within the response:**
    ```javascript
    console.log(response.sprites.front_default); // URL of front image
    ```

4. **Accessing an array within the response:**
    ```javascript
    console.log(response.abilities); // Array of ability objects
    ```

5. **Accessing the first item of an array within the response:**
    ```javascript
    console.log(response.abilities[0]); // First ability object
    ```

6. **Accessing a key of a specific item of an array within the response:**
    ```javascript
    console.log(response.abilities[0].ability.name); // "multitype"
    ```

---

##  **2. Charizard**

1. **Accessing a level 1 property (e.g., `name`, `weight`):**
    ```javascript
    console.log(response.name);   // "charizard"
    console.log(response.weight); // 905
    ```

2. **Accessing an object within the response:**
    ```javascript
    console.log(response.sprites); // Object with image URLs
    ```

3. **Accessing a specific key in the object within the response:**
    ```javascript
    console.log(response.sprites.front_default); // URL of Charizard's front image
    ```

4. **Accessing an array within the response:**
    ```javascript
    console.log(response.abilities); // Array of ability objects
    ```

5. **Accessing the first item of an array within the response:**
    ```javascript
    console.log(response.abilities[0]); // First ability object
    ```

6. **Accessing a key of a specific item of an array within the response:**
    ```javascript
    console.log(response.abilities[0].ability.name); // "blaze"
    console.log(response.abilities[1].ability.name); // "solar-power"
    ```

---

##  **3. Gengar**

1. **Accessing a level 1 property (e.g., `name`, `weight`):**
    ```javascript
    console.log(response.name);   // "gengar"
    console.log(response.weight); // 405
    ```

2. **Accessing an object within the response:**
    ```javascript
    console.log(response.sprites); // Object with image URLs
    ```

3. **Accessing a specific key in the object within the response:**
    ```javascript
    console.log(response.sprites.front_default); // URL of Gengar's front image
    ```

4. **Accessing an array within the response:**
    ```javascript
    console.log(response.abilities); // Array of ability objects
    ```

5. **Accessing the first item of an array within the response:**
    ```javascript
    console.log(response.abilities[0]); // First ability object
    ```

6. **Accessing a key of a specific item of an array within the response:**
    ```javascript
    console.log(response.abilities[0].ability.name); // "cursed-body"
    ```

---

