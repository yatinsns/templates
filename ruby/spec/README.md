This is where all tests files will go.

###Naming convention:
To test 'abc.rb', create spec file 'abc_spec.rb'

### Example test:

	require_relative "../abc.rb"

	describe "Abc" do
  	  it "shoud test something" do
    	    result = <some func call>
    	    result.should eql <desired value>
  	  end
	end


