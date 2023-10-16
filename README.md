To launch the project, follow these steps:

1. Clone the project repository to your computer using the following link:
git clone https://github.com/an1keenko/employees-express.git

2. Open the terminal (or command prompt) and navigate to the project's root directory.
cd employees-react-express

3. Install dependencies for the server-side of the project. Enter the following command in the terminal:
npm install

4. Rename the file `.env.local` to `.env`.

5. Generate types:
npx prisma generate

6. Create the database and perform migration:
npx prisma migrate dev

7. Navigate to the client directory and install dependencies for the client-side of the project.
cd client
npm install

8. Return to the project's root directory.
cd ..

9. Launch the project by entering the following command in the terminal:
npm run dev

10. Open your browser and go to http://localhost:3000 to view the running project.

A successful project launch should display a list of employees in your browser. If any issues occur during installation or project startup, ensure that all the steps above have been correctly executed according to the instructions.
Feel free to copy and paste this formatted version!