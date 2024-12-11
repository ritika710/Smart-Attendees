# Smart Attendees : Face-Recognition-Attendance-Management-System

Attendance Management System based on Face Recognition using Python and OpenCV.

---

## Code Requirements
- **OpenCV**: `pip install opencv-python`
- **Tkinter**: Available in Python by default.
- **PIL**: `pip install Pillow`
- **Pandas**: `pip install pandas`

---

## What Steps You Have to Follow?
1. Download the repository.
2. Create a `TrainingImage` folder in the project.
3. Open `AMS_Run.py` and change all paths to match your system paths.
4. Run `AMS_Run.py`.

---

## Project Structure
1. **Add Face Data**:  
   - Enter your ID and name in the input box.
   - Click on the **Take Images** button.
   - The system will collect 200 images of your face and save them in the `TrainingImage` folder.

2. **Train the Model**:  
   - Click on the **Train Image** button.  
   - Training will take 5–10 minutes (depending on data for 10 people).

3. **Automatic Attendance**:  
   - Click on **Automatic Attendance**.  
   - The system will fill attendance by recognizing faces using the trained model (saved in `TrainingImageLabel`).  
   - A `.csv` file of attendance will be created based on time and subject.

4. **Database Integration**:  
   - Install WAMPServer.  
   - Update the database name in `AMS_Run.py`.

5. **Manual Attendance**:  
   - Use the **Manually Fill Attendance** button in the UI to fill attendance without face recognition.  
   - It will create a `.csv` file and store it in the database.

---

## Notes
- High processing power is required.
- Noisy images can reduce accuracy; ensure good-quality images.
