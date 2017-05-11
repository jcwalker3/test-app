# test-app

    public function setFromConnection ($connection = null) { $this->from_connection = $connection; }
    public function setFromDatabase ($database = null) { $this->from_database = $database; }

    public function setToConnection ($connection = null) { $this->to_connection = $connection; }
    public function setToDatabase($database = null) { $this->to_database = $database; }

    public function setScrubbedData($setting = true) { $this->scrub_data = $setting; }
    public function setRequestedTables($requestedTables = array()) { $this->requested_tables = $requestedTables; }
    public function setExcludeTables($excludedTables = array()) { $this->excluded_tables = $excludedTables; }
    public function setIncludeStoredProcedures($setting = true) { $this->stored_procedures = $setting; }
    public function setIncludeTableViews($setting = true) { $this->table_views = $setting; }
    public function setIncludeTableData($setting = true) { $this->table_data = $setting; }
    public function setExcludeDataFromTable($excluded_data = array()) { $this->excluded_table_data = $excluded_data; }
    public function setLimitedDataFromTable($limitedData = array()) { $this->limit_table_data = $limitedData; }
    public function setResumePath($path = null) { $this->_store_dir = $path; }
