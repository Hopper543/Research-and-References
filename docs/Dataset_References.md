# Dataset References for MAITRI Project

## Primary Datasets for Model Development

### 1. FER2013 - Facial Expression Recognition
**Source**: https://www.kaggle.com/datasets/msambare/fer2013

**Dataset Characteristics**:
- **Size**: 35,887 grayscale images
- **Resolution**: 48x48 pixels
- **Emotions**: 7 classes (angry, disgust, fear, happy, sad, surprise, neutral)
- **Split**: Training (28,709), PublicTest (3,589), PrivateTest (3,589)

**Space Application Considerations**:
- ✅ Large dataset size for robust training
- ✅ Standardized emotion categories
- ❌ Laboratory conditions vs. space environments
- ❌ Limited ethnic and cultural diversity

### 2. RAVDESS - Ryerson Audio-Visual Database
**Source**: https://zenodo.org/record/1188976

**Dataset Characteristics**:
- **Modality**: Audio and video
- **Actors**: 24 (12 male, 12 female)
- **Recordings**: 7,356 files
- **Emotions**: 8 classes (neutral, calm, happy, sad, angry, fearful, disgust, surprised)
- **Intensity**: Normal and strong emotions

**Space Application Considerations**:
- ✅ High quality professional recordings
- ✅ Multiple modalities (audio + video)
- ✅ Controlled emotional expressions
- ❌ Studio environment vs. space station acoustics

### 3. TESS - Toronto Emotional Speech Set
**Source**: https://tspace.library.utoronto.ca/handle/1807/24487

**Dataset Characteristics**:
- **Actors**: 2 female speakers
- **Recordings**: 2,800 audio files
- **Emotions**: 7 classes (anger, disgust, fear, happiness, pleasant surprise, sadness, neutral)
- **Content**: 200 target words in carrier phrases

**Space Application Considerations**:
- ✅ Very clear emotional articulation
- ✅ Consistent recording quality
- ❌ Limited speaker diversity
- ❌ Scripted vs. spontaneous speech

## Dataset Integration Strategy

### Cross-Dataset Validation
- Train on FER2013, validate on RAVDESS facial components
- Combine RAVDESS and TESS for robust speech emotion training
- Ensure consistent emotion category mapping across datasets

### Space Environment Considerations
- Account for potential domain shift from Earth to space conditions
- Plan for data augmentation simulating space station environments
- Consider cultural variations in emotional expression among international crews

### Ethical Usage
- All datasets are publicly available for research purposes
- Appropriate citations required for academic publications
- Privacy considerations for future space deployment
