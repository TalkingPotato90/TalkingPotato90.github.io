---
layout: post
title: "[ERP] Project Small Works 0"
date: 2024-09-28 16:52 +0900
description: 전사적 자원 관리 웹 만들기 with ljhee92
category: [ERP, Project]
tags: []
pin: false
math: true
mermaid: true
---
# Small Works

## 개요

## 팀 구성

## 기간
기획 : 2024.09.28 ~ 2024.10.06

개발 : ? 

## 개발 환경
인텔리제이
오라클
맥
자바 21

## 기술 스택
리액트 JPA 스프링부트 gradle

## 주요 기능
- 출퇴근기록 월별 아카이빙
- RFID를 사용한 출퇴근 기록관리

## 필요한거 TODO
1. 원격 접속 가능한 데이터베이스
2. 리액트 공부
3. 진급/전보 기록 데이터베이스 구성을 어떻게 할 것인가
4. 급여관리 나중에 추가

## 기능 목록
### 시스템 관리자
1. 코드관리
2. 권한관리
    1. 관리자 관리
        - 생성되어있는 사용자 계정에 권한을 부여하거나 회수하는 기능
    2. 권한 그룹 관리
        - 새로운 권한 그룹을 생성하는 기능
        - 생성된 권한 그룹의 권한 목록을 수정하는 기능

### 사용자
- 일반 관리자는 기본적으로 일반 사용자의 모든 기능을 사용가능하다
#### 일반사용자
1. 인사 정보 화면
    1. 로그인하면 첫화면으로 인사정보가 보인다
    2. 연락처 / 비밀번호 변경 가능
    3. 사진의 변경은 일반관리자의 승인 필요
2. 근태 관리 화면

#### 일반관리자
1. 인사 정보 화면
    1. 로그인하면 첫화면으로 인사정보가 보인다
    2. 연락처 / 사진 / 비밀번호 변경 가능
2. 근태 관리 화면
    1. 개인 근태 조회
    2. 팀 근태 조회


