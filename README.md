# loginfornode
sistem login menggunakan nodejs

# library 
    express = require('express');
    path = require('path'),
    favicon = require('serve-favicon'),
    logger = require('morgan'),
    cookieParser = require('cookie-parser'),
    bodyParser = require('body-parser'),
    session = require('express-session'),
    passport = require('passport'),
    LocalStrategy = require('passport-local').Strategy,
    expressValidator = require('express-validator'),
    multer = require('multer'),
    upload = multer({dest: './uploads'}),
    flash = require('connect-flash'),
    bcrypt = require('bcryptjs'),
    mongo = require('mongodb'),
    mongoose = require('mongoose'),
