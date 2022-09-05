# Project-Data-Dig

/* Rick owens clothing from Strobe FW 22 */


CREATE TABLE rick_clothes(ID INTEGER PRIMARY KEY,
    name TEXT,
    price INTEGER,
    gender TEXT, 
    size Text,
    color TEXT,
    material TEXT,
    popularity INTEGER,
    model_height_cm INTEGER);
    
INSERT INTO rick_clothes VALUES (1, "large_draestring", 1200, "Male", "OS", "teal", "cow_leather", 0, 0);
INSERT INTO rick_clothes VALUES (2, "oversized_round_neck", 585, "Male", "Small", "aqua", "new_wool", 1, 189); 
INSERT INTO rick_clothes VALUES (3, "granbury_hoodie", 600, "Male", "Large", "black", "cotton", 5, 185); 
INSERT INTO rick_clothes VALUES (4, "strobe_outershirt", 2475, "Male", "48", "green", "lamb_leather", 8, 190); 
INSERT INTO rick_clothes VALUES (5, "turbodrk_hi", 170, "Male", "11", "black", "upper_cotton", 2, 0); 
INSERT INTO rick_clothes VALUES (6, "geth_belas", 995, "Male", "48", "orange", "cotton", 10, 190); 
INSERT INTO rick_clothes VALUES (7, "geth_jeans", 735, "Male", "OS", "teal", "ccotton", 9, 160); 


SELECT * FROM rick_clothes;

SELECT MIN(popularity), MAX(popularity), (popularity)
FROM rick_clothes;
