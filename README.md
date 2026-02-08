# 🚗 Przewidywanie Ryzyka Wypadków Drogowych (Road Accident Risk Prediction)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Sklearn-Latest-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![SHAP](https://img.shields.io/badge/XAI-SHAP-red)

## 📋 Przegląd Projektu
Celem projektu jest stworzenie i porównanie modeli uczenia maszynowego (ML) oraz głębokiego (DL) do przewidywania poziomu ryzyka wypadku (`accident_risk`) na podstawie parametrów infrastruktury drogowej i warunków środowiskowych.

Projekt kończy się analizą **XAI (Explainable AI)**, która wyjaśnia, dlaczego model uznaje dany odcinek drogi za bezpieczny lub niebezpieczny.

---

## 🗂️ Dane
* **Źródło:** [Kaggle - Road Accident Dataset](https://www.kaggle.com/datasets/chetanmittal033/road-accident-dataset)
* **Wielkość próby:** 10 000 rekordów.
* **Zmienna celu:** `accident_risk` (ciągła, znormalizowana).
* **Kluczowe cechy:** `speed_limit`, `curvature`, `lighting`, `weather`, `road_type`.

---

## 🚀 Jak uruchomić?
1. Sklonuj repozytorium.
2. Zainstaluj wymagane pakiety:
   ```bash
   pip install -r requirements.txt