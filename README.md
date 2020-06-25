# Spring Data JPA 3 : Many-to-Many
## Spring Data JPA 3 : Many-to-Many

Hibernate: create table wizard_course (wizard_id bigint not null, cours_id bigint not null) engine=InnoDB <br>
Hibernate: alter table wizard_course add constraint FKmeilig281iq7ok9xxf1hme7dq foreign key (cours_id) references course (id) <br>
Hibernate: alter table wizard_course add constraint FK403omq5ol57tkag4s9dfjsep3 foreign key (wizard_id) references wizard (id) <br>


