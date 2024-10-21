# 🖼️ OpenCV Playground

<div align="center">
  
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)


**An interactive web platform for exploring and experimenting with OpenCV image processing techniques** 🚀

[Demo](https://your-demo-link.com) · [Report Bug](https://github.com/Sebastianx0808/cv-lab/issues) · [Request Feature](https://github.com/Sebastianx0808/cv-lab/issues)

</div>

## 🌟 About The Project

OpenCV Playground is an intuitive web platform that brings the power of computer vision to your browser. Whether you're a student learning image processing, a developer exploring OpenCV capabilities, or a professional looking to quickly prototype CV operations, this platform provides a seamless interface to experiment with various image processing techniques.

### ✨ Key Features

- 🖼️ **Interactive Image Upload**: Drag and drop interface for easy image uploading
- 🛠️ **Multiple Processing Operations**:
  - Basic Operations (Grayscale, Blur, Rotation)
  - Edge Detection (Canny, Sobel)
  - Color Space Manipulations
  - Thresholding Techniques
  - Contour Detection
  - Feature Detection
- 👁️ **Real-time Preview**: See changes as you adjust parameters
- 📊 **Side-by-side Comparison**: Compare original and processed images
- 💾 **Download Processed Images**: Save your results locally
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0 or higher)
- Python (v3.8 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sebastianx0808/cv-lab.git
   cd cv-lab
   ```

2. **Set up the Frontend**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Set up the Backend**
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   python app.py
   ```

4. **Create a `.env` file in the backend directory**
   ```env
   FLASK_APP=app.py
   FLASK_ENV=development
   SECRET_KEY=your-secret-key
   ```

## 🎯 Usage

1. **Upload an Image**
   - Drag and drop an image onto the upload area
   - Or click to select an image from your files

2. **Choose Processing Operation**
   - Select from available image processing operations
   - Adjust parameters using the intuitive controls

3. **View and Compare**
   - See the processed result in real-time
   - Use the comparison slider to analyze changes

4. **Download Results**
   - Download the processed image
   - Save multiple versions with different operations

## 🛠️ Technical Architecture

### Frontend
- **React.js**: UI development
- **Tailwind CSS**: Styling
- **Axios**: API communication
- **React Router**: Navigation
- **React Query**: Data fetching

### Backend
- **Flask**: Server framework
- **OpenCV**: Image processing
- **NumPy**: Numerical operations
- **Pillow**: Image handling
- **Flask-CORS**: Cross-origin support

## 🗺️ Roadmap

- [x] Basic project setup
- [x] Image upload functionality
- [x] Basic image processing operations
- [ ] Advanced processing operations
- [ ] User authentication
- [ ] Save processing history
- [ ] Batch processing
- [ ] Custom filter creation
- [ ] Mobile app version

## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.


## 🙏 Acknowledgments

* [OpenCV](https://opencv.org/)
* [React](https://reactjs.org/)
* [Flask](https://flask.palletsprojects.com/)
* [Tailwind CSS](https://tailwindcss.com/)
* [React Dropzone](https://react-dropzone.js.org/)

---

<div align="center">
  
⭐️ Star this repository if you find it helpful!

</div>
