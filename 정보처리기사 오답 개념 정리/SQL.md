

### 관계대수 표현


---

### SQL DCL

- 권한 부여
GRANT
```sql
GRANT DML on 테이블명 to 사용자명 with grant option;
GRANT SELECT ON STUDENT to PUBLIC( ## 모든 사용자);
```

- 권한 회수
REVOKE
```sql
REVOKE DML on 테이블명 from 사용자명;
```

---

- 인덱스 생성

```sql
create index 이름 on 테이블명(필드...);
```

