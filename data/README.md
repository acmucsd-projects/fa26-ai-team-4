# fa26-ai-team-4

## Source

https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/

## Cleaned Method

Removed pictures with no faces, 2 faces, low face scores, no gender information.
Then removed people with only one unique age.

## Columns

name, directory, age, gender

## Usage

To crop the face in Matlab run
img(face_location(2):face_location(4),face_location(1):face_location(3),:)