<img width="938" height="451" alt="Screenshot 2026-05-08 224911" src="https://github.com/user-attachments/assets/36dcbd5b-234e-40af-be91-b77ba86a71f2" />
<img width="950" height="418" alt="Screenshot 2026-05-08 225031" src="https://github.com/user-attachments/assets/99961d2e-eda5-4a4b-b084-ecfb0422fec8" />
<img width="932" height="390" alt="Screenshot 2026-05-08 225047" src="https://github.com/user-attachments/assets/d4b6684c-47ee-4fdf-b8ad-323b8d826dac" />
<img width="906" height="301" alt="Screenshot 2026-05-08 225056" src="https://github.com/user-attachments/assets/2827b6a3-559d-4537-94d8-8556d29a361a" />

This page show a table of cars. The car information come from node04 API route. I used fetch in JavaScript to get the cars and put them inside the table.

Instruction:
Click delete to remove a row from the table.
Click update to change the car information like brand, year, make, or color.
When the user click delete, the page send a DELETE request to the server. The car is removed, then the table load again so the change can show.
When the user click update, the page ask for the new brand, year, make, and color. After that it send a PUT request to the server and update that car.
One problem I had was the page was not showing the data at first. I checked my route and made sure the fetch URL match the route in my Node file. After that the cars showed in the table.


