Welcome to the AngularJS-FORM-Validation wiki!



# atrrtibutes:

* ng-required
* ng-minlength
* ng-maxlength
* ng-patterm

## inputtype:

* email
* url
* number



`<input type="text" id="username" name="fullname" class="from-control"`
`ng-model="editableEmployee.fullname" ng-required="true"`
`ng-minlength="3" ng-maxlength="6" />`
`<span class="help-block ng-if="employee.fullname.$error.required"> full name is required</span>`
`<span class="help-block ng-if="employee.fullname.$error.pattern"> name start with A</span>`

# email:
`<input type="email" id="email" name="email" class="from-control"`
`ng-model="editableEmployee.email" ng-required="true"`
`ng-minlength="3"ng-maxlength="6" ng-pattern="/^A/" />`
`<span class="help-block hide> email is required</span>`

## url:
`<input type="url" id="url" name="url" class="from-control"`
`ng-model="editableEmployee.url" ng-required="true"`
`ng-minlength="3" ng-maxlength="6" />`
`<span class="help-block hide> url is required</span>`

## ng-pattern:

`ng-pattern="/^A/"`

* name starts with captial A:
