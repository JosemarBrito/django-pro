# django-pro
Repositório para aprendizagem e criação de uma pagina web com Framework Django

[![Build Status](https://travis-ci.org/JosemarBrito/django-pro.svg?branch=main)](https://travis-ci.org/JosemarBrito/django-pro)
[![codecov](https://codecov.io/gh/JosemarBrito/django-pro/branch/main/graph/badge.svg?token=SR25BFQ3UL)](https://codecov.io/gh/JosemarBrito/django-pro)



  abaixo do '''''python-version: 3.8''''' 
  
 - name: Copying configurations
      run: |
        cp contrib/env-sample .env
        
    
        
        
        
        """abaixo de Flake8"      
        
   - name: Test with pytest
      run: |
        pipenv run pytest pybrito --cov=pybrito
        
        - name: Posting Coverage
      env:
        CODECOV_TOKEN: "77ac6bc4-5c19-40c4-a4bd-8bca2996dec1"
      run: |
        pipenv run codecov
        
        