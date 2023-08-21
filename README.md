# Postman
console.log(+resp.qa_salary_after_6_months)

pm.test("Check parameter qa_salary_after_12_months is equal salary*2,7 from request", function () {
    pm.expect(+resp.qa_salary_after_12_months).to.eql(+req.salary * 2.7);
});
