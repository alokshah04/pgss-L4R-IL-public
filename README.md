  <a href="https://colab.research.google.com/github/alokshah04/pgss-L4R-IL-public/blob/main/student_colab.ipynb" 
  target="_parent">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
  
# Imitation Learning Lab — HalfCheetah

Behavior cloning homework for PGSS. Students train a MuJoCo HalfCheetah to run
by imitating a pretrained expert policy using supervised learning.

## Files

| File | Description |
|------|-------------|
| `student_colab.ipynb` | Student notebook — key functions blanked out for students to implement |
| `experts/` | Pretrained SAC expert policy for HalfCheetah-v5 |
| `requirements.txt` | Python dependencies |

## Setup (local)

```bash
conda create -n il-lab python=3.11 -y
conda activate il-lab
pip install -r requirements.txt
jupyter notebook student.ipynb
```

## Running on Colab

Open `student.ipynb` in Colab, switch to a T4 GPU runtime, and run Step 0 first.
Video recording cells are local-only and should be skipped on Colab.
